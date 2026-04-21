Synthetic coordination scenarios dataset

Files:
- synthetic_coordination_scenarios.csv: paired synthetic dataset for 1,000 firms under two scenarios:
  1) baseline_sporadic
  2) ai_enabled_coordination
- synthetic_coordination_summary.csv: mean comparison across the two scenarios

Important limitation:
This dataset is synthetic and assumption-driven. It is calibrated to be directionally consistent with the paper's empirical findings, but it does NOT constitute real-world validation or causal proof.

Core design logic:
- Baseline values reflect low-intensity, sporadic collaboration.
- AI-enabled scenario reduces effective trust barriers and improves information sharing, joint planning, matching, utilization, and service metrics.

Topline mean effects in the synthetic dataset:
                        metric  baseline_mean  ai_mean  absolute_change  percent_change
horizontal_collaboration_index       3.056730 4.077740         1.021010       33.402034
           empty_backhaul_rate       0.166486 0.104604        -0.061882      -37.169492
      vehicle_utilization_rate       0.817673 0.889182         0.071509        8.745428
         matching_success_rate       0.651296 0.819155         0.167859       25.773074
collaboration_events_per_month       5.432000 9.708000         4.276000       78.718704
    service_level_on_time_rate       0.861481 0.892069         0.030588        3.550630
     emissions_intensity_index       0.928381 0.852361        -0.076020       -8.188448

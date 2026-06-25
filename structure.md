Continuous-Quality-Improvement-Knowledge-Portal/
│
├── README.md
├── LICENSE
├── CONTRIBUTING.md
│
├── docs/
│   ├── ci-os_outline.md
│   ├── digital_twin_overview.md
│   ├── signal_flow_dag.md
│   ├── governance_model.md
│   ├── role_catalog.md
│   └── simulation_engine_spec.md
│
├── roles/
│   ├── operator/
│   │   ├── frontline_operator.json
│   │   ├── ci_enabled_operator.json
│   │   └── human_review_queue_specialist.json
│   ├── supervision/
│   │   └── team_lead_supervisor.json
│   ├── engineering/
│   │   ├── ci_specialist.json
│   │   ├── workflow_orchestrator.json
│   │   ├── automation_engineer.json
│   │   └── maintenance_reliability_engineer.json
│   ├── governance/
│   │   ├── cqi_governance_lead.json
│   │   ├── audit_risk_officer.json
│   │   └── safety_compliance_officer.json
│   ├── architecture/
│   │   └── ci_os_architect.json
│   ├── leadership/
│   │   └── executive_sponsor.json
│   ├── product/
│   │   └── product_owner_value_stream_manager.json
│   ├── data/
│   │   └── data_analyst_process_mining_specialist.json
│   └── customer/
│       └── customer_experience_liaison.json
│
├── digital_twin/
│   ├── simulation_engine/
│   │   ├── engine_schema.json
│   │   ├── digital_twin_simulation_controller.json
│   │   ├── channels.json
│   │   ├── routing_table.json
│   │   ├── role_action_bindings.json
│   │   └── state_model.json
│   │
│   ├── signal_maps/
│   │   ├── ngode_signal_map.json
│   │   ├── digital_twin_signal_map.json
│   │   └── signal_flow_dag.txt
│   │
│   ├── scenarios/
│   │   ├── baseline_scenario.json
│   │   ├── drift_scenario.json
│   │   ├── override_scenario.json
│   │   ├── inversion_scenario.json
│   │   └── stress_test_scenario.json
│   │
│   └── engines/
│       ├── ngode/
│       │   ├── ngode_schema.json
│       │   ├── ngode_channels.json
│       │   └── ngode_role_bindings.json
│       ├── fra01/
│       │   └── fra01_engine.json
│       ├── tbtf/
│       │   └── tbtf_engine.json
│       └── iip_iosefe/
│           └── iip_iosefe_engine.json
│
├── governance/
│   ├── policies/
│   │   ├── escalation_policy.md
│   │   ├── override_governance_policy.md
│   │   └── emergency_stabilization_protocol.md
│   ├── audits/
│   │   ├── audit_templates/
│   │   └── audit_checklists/
│   └── compliance/
│       ├── safety_standards.md
│       └── quality_standards.md
│
├── checklists/
│   ├── operational_checklists/
│   ├── governance_checklists/
│   └── simulation_checklists/
│
├── ui/
│   ├── wireframes/
│   │   ├── inventory_dashboard.html
│   │   ├── checklist_editor.html
│   │   └── checklist_runner.html
│   └── components/
│       └── shared_ui_components.json
│
└── tools/
    ├── scripts/
    │   ├── validate_schema.py
    │   ├── run_simulation.py
    │   └── generate_report.py
    └── utilities/
        └── json_linter.py

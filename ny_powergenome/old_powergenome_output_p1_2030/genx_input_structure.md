# arrangement of files for genx input structure
NOTE: Not all files are required. It depends on the model being run.
    ```
    ├── policies
    │   ├── Capacity_reserve_margin.csv
    │   ├── CO2_cap.csv
    │   ├── Minimum_capacity_requirement.csv
    │   ├── Energy_share_requirement.csv
    │   └── Hydrogen_demand.csv
    │
    ├── resources
    │   ├── Electrolyzer.csv
    │   ├── Storage.csv
    │   ├── Thermal.csv
    │   ├── Vre.csv
    │   ├── Vre_stor.csv
    │   ├── Resource_multistage_data.csv
    │   └── policy_assignments
    │       ├── Resource_minimum_capacity_requirement.csv
    │       ├── Resource_maximum_capacity_requirement.csv
    │       ├── Resource_hourly_matching.csv
    │       ├── Resource_hydrogen_demand.csv
    │       ├── Resource_energy_share_requirement.csv
    │       └── Resouce_capacity_reserve_margin.csv
    │
    ├── settings
    │   ├── genx_settings.yml
    │   ├── highs_settings.yml
    │   ├── time_domain_reduction_settings.yml
    │   ├── cplex_settings.yml
    │   ├── gurobi_settings.yml
    │   ├── clp_settings.yml
    │   └── multi_stage_settings.yml
    │
    ├── system
    │   ├── Demand_data.csv
    │   ├── Fuels_data.csv
    │   ├── Generators_variability.csv
    │   ├── Network.csv
    │   ├── Period_map.csv
    │   ├── Operational_reserves.csv
    │   ├── Vre_and_stor_solar_variability.csv
    │   └── Vre_and_stor_wind_variability.csv
    |
    ├── Run.jl 
    ```

# rearranging input files from powergenome into new genx format
    - POLICES: # DONE
        - Capacity_reserve_margin.csv
        - CO2_cap.csv
        - Minimum_capacity_requirement.csv
        - Energy_share_requirement.csv
        - Hydrogen_demand.csv
        
    - RESOURCES: # DONE
        - Electrolyzer.csv
        - Storage.csv
        - Thermal.csv
        - Vre.csv
        - Vre_stor.csv
        - Resource_multistage_data.csv

        - POLICY_ASSIGNMENTS:
            - Resource_minimum_capacity_requirement.csv
            - Resource_maximum_capacity_requirement.csv
            - Resource_hourly_matching.csv
            - Resource_hydrogen_demand.csv
            - Resource_energy_share_requirement.csv
            - Resouce_capacity_reserve_margin.csv

    - SETTINGS:
        - genx_settings.yml
        - highs_settings.yml
        - time_domain_reduction_settings.yml
        - cplex_settings.yml
        - gurobi_settings.yml
        - clp_settings.yml
        - multi_stage_settings.yml

    - SYSTEM: 
        - Demand_data.csv
        - Fuels_data.csv
        - Generators_variability.csv
        - Network.csv
        - Period_map.csv
        - Operational_reserves.csv
        - Vre_and_stor_solar_variability.csv
        - Vre_and_stor_wind_variability.csv

        NOTES:
            -   Demand_data.csv RENAMED FROM Load_data.csv 
            not found:
            -   Vre_and_stor_solar_variability.csv
            -   Vre_and_stor_wind_variability.csv
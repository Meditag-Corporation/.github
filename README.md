# .github
About Meditag

# Meditag System Architecture: Hierarchical Software Installations

MeditagCloudCore
  |
  +-- MeditagCloudRegionalNamibia
  |     |
  |     +-- Tenant 1
  |     |     |
  |     |     +-- Enterprise 1 (EHR)
  |     |     |     |
  |     |     |     +-- Node 1 (EHR Facility)
  |     |     |     +-- Node 2 (EHR Facility)
  |     |     |
  |     |     +-- Enterprise 3 (LIMS)
  |     |           |
  |     |           +-- Node 3 (LIMS Facility)
  |     |           +-- Node 4 (LIMS Facility)
  |     |
  |     +-- Tenant 2
  |           |
  |           +-- Enterprise 2 (LIMS)
  |           |     |
  |           |     +-- Node 5 (LIMS Facility)
  |           |     +-- Node 6 (LIMS Facility)
  |           |
  |           +-- Enterprise 4 (EHR)
  |                 |
  |                 +-- Node 7 (EHR Facility)
  |                 +-- Node 8 (EHR Facility)
  |
  +-- MeditagCloudRegionalSouthAfrica
        |
        +-- Tenant 3
        |     |
        |     +-- Enterprise 5 (EHR)
        |     |     |
        |     |     +-- Node 9 (EHR Facility)
        |     |     +-- Node 10 (EHR Facility)
        |     |
        |     +-- Enterprise 6 (LIMS)
        |           |
        |           +-- Node 11 (LIMS Facility)
        |           +-- Node 12 (LIMS Facility)
        |
        +-- Tenant 4
              |
              +-- Enterprise 7 (EHR)
              |     |
              |     +-- Node 13 (EHR Facility)
              |     +-- Node 14 (EHR Facility)
              |
              +-- Enterprise 8 (LIMS)
                    |
                    +-- Node 15 (LIMS Facility)
                    +-- Node 16 (LIMS Facility)

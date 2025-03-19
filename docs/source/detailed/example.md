# &lt;Psyche_Mission_Dictionary&gt; 

Submitter: Ernest Cisneros, ASU


## &lt;psyche:&gt; 

Submitter: Ernest Cisneros

```
   <Discipline_Area>
     <psyche:Psyche_Parameters>
       <psyche:mission_phase_name>PHASE</psyche:mission_phase_name>
       <psyche:orbit>ORBIT_NUMBER</psyche:orbit>
       <psyche:release_number>RELEASE_NUMBER</psyche:release_number>
       <psyche:spacecraft_clock_partition>SCLK_PARTITION</psyche:spacecraft_clock_partition>
       <psyche:spacecraft_clock_start>SCLK_START</psyche:spacecraft_clock_start>
       <psyche:spacecraft_clock_stop>SCLK_STOP</psyche:spacecraft_clock_stop>
       <psyche:spacecraft_clock_start_corrected>SCLK_START_CORRECTED</psyche:spacecraft_clock_start_corrected>
       <psyche:spacecraft_clock_stop_corrected>SCLK_STOP_CORRECTED</psyche:spacecraft_clock_stop_corrected>
       <psyche:spacecraft_fsw_dictionary_version>SC_FSW_DICTIONARY_VERSION</psyche:spacecraft_fsw_dictionary_version>
       <psyche:spacecraft_active_flight_computer>SC_ACTIVE_COMPUTER</psyche:spacecraft_active_flight_computer>
     </psyche:Psyche_Parameters>
   </Discipline_Area>
```

### Mission Phase

This parameter is enumerated to a known phase name, corresponding to specific
date ranges of the mission.

   * test The Psyche mission phase used for general testing purposes.
   * preflight The Psyche mission phase used for preflight operations.
   * atlo The Psyche mission phase used for ATLO.
   * launch The Psyche mission phase used for spacecraft launch.
   * ico The Psyche mission phase used for the initial checkout (ICO), lasting 100 days.
   * cruise_1 The Psyche mission phase used for the cruise 1 period, lasting 26 months.
   * mga The Psyche mission phase used for the Mars gravity assist, lasting 62 days.
   * cruise_2 The Psyche mission phase used for the cruise 2 period, lasting 36 months.
   * approach The Psyche mission phase used for the approach to 16 Psyche, last 100 days.
   * orbital_operations bThe Psyche mission phase used for the entire orbital operations period, lasting 26 months.
   * orbit_a The Psyche mission phase used for orbit A operations, lasting 56 days.
   * orbit_b1 The Psyche mission phase used for orbit B1 operations, lasting 92 days.
   * orbit_b2 The Psyche mission phase used for orbit B2 operations, lasting 100 days.
   * orbit_c The Psyche mission phase used for orbit C operations, lasting 100 days.
   * orbit_d The Psyche mission phase used for orbit D operations, lasting 100 days.
   * orbit_transfer_a_to_b1 The Psyche mission phase used for orbit transfer A-to-B1, lasting 17 days.
   * orbit_transfer_b1_to_d The Psyche mission phase used for orbit transfer B1-to-D, lasting 98 days.
   * orbit_transfer_d_to_c The Psyche mission phase used for orbit transfer D-to-C, lasting 90 days.
   * orbit_transfer_c_to_b2 The Psyche mission phase used for orbit transfer C-to-B2, lasting 23 days.

### Flight Software Dictionary

This parameter is enumerated to known version of the flight software dictionary 
in use during the mission.

   * 5_4_2_1 Version 5.4.2.2 of the Psyche FSW dictionary.
   * 5_4_2_1 Version 5.4.2.1 of the Psyche FSW dictionary.


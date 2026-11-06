Oct 28, 2026
Ernest Cisneros, Psyche Science Data Center, ASU

# Introduction
   1. Purpose of this User’s Guide
   1. Audience
   1. Applicable Documents

# Overview of the Psyche Mission Local Data Dictionary

The Psyche Local Data Dictionary (LDD), commonly referred to as the Psyche
Mission Dictionary, was designed during the projects phase C and D development,
and the first cruise flight segment. The dictionary is based on the 1.22.0 PDS
information model. Attributes can be found in the Discipline_Area section of a
PDS4 label.

Steward: Ernest Cisneros, Psyche Science Data Center, ASU, ecisneros@asu.edu

# Organization of Classes and Attributes

The following classes and attributes are defined for the Psyche mission. 
SLCK values can be provide with or without a clock partition, and in either 
byte or decimal based notation. If the SCLK is given without a clock partition,
the spacecraft_clock_partition keyword must be defined. Example of properly 
formatted SLCK values include: 0/0792731143-0277070, 0792731143-0277070, or
0792731143.2642345.

## Mission Wide Classes and Attributes

The following attributes are defined for the mission (Psyche_Mission super-class), and found within the Psyche_Parameters class.

[psyche:mission_phase_name](#mission_phase_name) - This class contains an enumerated text string corresponding to the specific mission phase that a product was acquired in. If a product spans a phase boundary, this attribute should be set to phase in which the observation began acquisition.
[psyche:orbit](#orbit) - This class contains an integer value corresponding to the orbit number, in that particular orbital operations phase.
[psyche:release_number](#release_number) - This class contains an integer value corresponding to the release number that a particular product was associated with.
[psyche:spacecraft_clock_partition](#spacecraft_clock_partition) - This class contains the integer value corresponding to the current mission clock partition for the current observation.
[psyche:spacecraft_clock_start](#spacecraft_clock_start) - This class contains the SCLK value at the start of the observation.
[psyche:spacecraft_clock_stop](#spacecraft_clock_stop) - This class contains the SCLK value at the end of the observation.
[psyche:spacecraft_clock_start_corrected](#spacecraft_clock_start_corrected) - This class contains the corrected SCLK value at the start of the observation.
[psyche:spacecraft_clock_stop_corrected](#spacecraft_clock_stop_corrected) - This class contains the corrected SCLK value at the end of the observation.
[psyche:spacecraft_fsw_dictionary_version](#spacecraft_fsw_dictionary_version) - This class contains an enumerated string value corresponding to the flight software dictionary being used the observation acquisition.  Acceptable values are: `'5_4_2_1' or '5_4_2_2'.
[psyche:spacecraft_active_flight_computer](#spacecraft_active_flight_computer) - This class contains an enumerated character value corresponding to which RCE was in control during the observation acquisition. Acceptable values are: `A' or `B'.


## Instrument Specific Classes and Attributes

As of version 1.1.0.0 of the mission dictionary, there is a defined Magnetometer_Parameters
and Imager_Parameters class, each containing instrument specific attributes. These classes
are contained within the super-class Psyche_Mission.

### Magnetometer Instrument Attributes

[psyche:magnetometer_instrument_id](#magnetometer_instrument_id) - This attribute contains the enumerated magnetometer ID for the observation.
[psyche:electronics_unit_id](#electronics_unit_id) - This attribute contains the mag electronics unit id for the observation.
[psyche:magnetometer_temperature](#magnetometer_temperature) - This attribute contains the mag temperature for the observation.
[psyche:magnetometer_frequency](#magnetometer_frequency) - This attribute contains the mag frequency for the observation.
[psyche:magnetometer_delay](#magnetometer_delay) - This attribute contains the mag delay value for the observation.
[psyche:magnetometer_sampling_frequency](#magnetometer_sampling_frequency) - This attribute contains the mag sampling frequency for the observation.

### Imager Instrument Attributes 

[psyche:imager_instrument_id](#imager_instrument_id) - This attribute contains the enumerated imager ID for the observation.


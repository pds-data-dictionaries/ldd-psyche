May 19, 2026
Ernest Cisneros, Psyche Science Data Center, ASU

> Note to authors who use this outline: The outline is a
> suggestion only. It includes the minimum of content needed to inform the
> dictionary user. Authors are expected to tailor the outline to their particular
> purposes, elaborating and providing context as needed.

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

The following attributes are defined for the mission.

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

At the time of this release, no instrument specific classes or attributes have
been defined. Additional work on the Imager, Magnetometer, Gamma Ray
Spectrometer, and Neutron Spectrometer PDS4 products may necessitate the
development of instrument specific classes and attributes, especially
post-Mars gravity assist, and certification of each instruments calibrated product pipeline.

# Definitions

*Give an alphabetical list of all classes and attributes
with complete definitions. (Useful ones, not silly ones like "The
map_projection_name attribute provides the name of the map projection.")*

*Include:*

- *Class or attribute name (indicate which it is; capitalize class names according to PDS4 standard)*
- *PDS4 data type (ASCII_Short_String_Collapsed, ASCII_Real, ASCII_Date, etc.)*
- *Definition in complete sentences*
- *Cardinality (minimum and maximum number of values permitted)*
- *Nillable, yes or no? Explain when it is appropriate to use a nil value*
- *Minimum and maximum numeric values, if applicable*
- *Minimum and maximum number of characters, if applicable*
- *List of valid values, if applicable.*

# Examples

*Give one or more examples of label snippets for real products, annotated as appropriate. 
Make sure the examples can be successfully validated using the latest version of the PDS4 
core dictionary and, of course, the dictionary described in this document.*

PDS4 Psyche Mission Dictionary User's Guide

2024-12-13
Ernest Cisneros (ecisneros@asu.edu)

<!-- Everything below this comment needs editing -->

# Introduction
   1. Purpose of this Users Guide

   This guide provide information regarding the Psyche mission dictionary and how to include the information covered by this dictionary in a product label.

   2. Audience

   This guide should be used by data providers creating and archiving products with the PDS, derived from instruments or other data acquired by the Psyche spacecraft.

   3. Applicable Documents

# Overview of the {name} Local Data Dictionary

*What is this dictionary for? What kinds of products might
use this dictionary? Who is the steward of this dictionary (person and node
name)? How often is it updated? To whom should questions about it be directed?
(Give an email address or link to a page with contact information.)*

# Organization of Classes and Attributes

*Give a schematic diagram or a list showing the hierarchy of
classes in order of appearance in label. Refer the reader to the Definitions
section for complete definitions. An example of such a list is given on the
page [Filling Out The Spectral Dictionary Classes](http://sbndev.astro.umd.edu/wiki/Filling_Out_the_Spectral_Dictionary_Classes#.3CCircular_FOV.3E)
on the PDS Small Bodies Node wiki. In this example the names of classes and attributes have hyperlinks to
their definitions further down the page, a useful lookup tool.*

*The author should take into consideration the complexity
of the dictionary when organizing this section.  If the hierarchy is large or
complicated, it may be helpful to break it down by class as shown in the
following subsections, but don’t forget to provide a high-level view of how the
classes relate to one another.*

## Class 1

*What is this class for?*

*Give a schematic diagram or a list of the attributes in this class in order of 
appearance in label. Refer reader to Definitions section for complete definitions.*

*Give label snippets showing use of the class and attributes, with annotations 
as appropriate. Refer reader to Examples section for complete examples.*

*Explain why some things are required and others are optional.*

*List and explain any rules that apply to this class (e.g. from Schematron).*

## Class 2

[repeat this subsection for each class]

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

```
<Discipline_Area>
   <psyche:Psyche_Parameters>
      <psyche:mission_phase_name> </psyche:mission_phase_name>
      <psyche:orbit_number> </psyche:orbit_number>
      <psyche:release_number> </psyche:release_number>
      <psyche:spacecraft_clock_partition> </psyche:spacecraft_clock_partition>
      <psyche:spacecraft_clock_start> </psyche:spacecraft_clock_start>
      <psyche:spacecraft_clock_stop> </psyche:spacecraft_clock_stop>
      <psyche:spacecraft_clock_start_corrected> </psyche:spacecraft_clock_start_corrected>
      <psyche:spacecraft_clock_stop_corrected> </psyche:spacecraft_clock_stop_corrected>
      <psyche:spacecraft_fsw_dictionary_version> </psyche:spacecraft_fsw_dictionary_version>
      <psyche:spacecraft_active_flight_computer> </psyche:spacecraft_active_flight_computer>
   </psyche:Psyche_Parameters>
</Discipline_Area>
```

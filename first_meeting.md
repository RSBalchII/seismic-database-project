Here's the summary formatted in Markdown:

# Project Overview

- **Main objective**: Monitor micro-seismic or seismic activity in the area, specifically related to oil rig operations.
- **Secondary objective**: Make the data useful and accessible for analysts.
- **Federally funded project**: Data will be stored on federal EDX (Energy Data Exchange).
- **DOE (Department of Energy) funded initiative**.

## Data Collection and Processing

- **Sensors**: Seismometers collecting data on event location and depth.
- **File formats**:
  - Original: SEG-D (Society of Exploration Geophysicists) format
  - Converted to: SEG-2 format
  - Final format: MiniSEED
- **Data processing**: Using ObsPy for analysis.

## Focus Areas

1. **CO2 injection effects**:

   - Did it cause more seismic activity?
   - Does data show triangulation of seismic activity?

2. **WAG (Water Alternating Gas) recovery**:

   - Method: Sweep with water, then sweep with CO2
   - Pressure: Up to 2000 psi on the well head

3. **CO2 tracking**:
   - Source: Power plants in Georgia and Kansas
   - Accounting: EPA tracks CO2 purchased and left in the ground
   - Tax implications: Companies receive tax credits

## Additional Context

- **EPA requirement**: Monitoring micro-seismic activity is mandatory.
- **Data volume**: Potentially millions of data columns and rows, uncertain number of tables.
- **Database access**: You have access to the server machine from previous work.
- **API**: Currently doesn't exist; considering using software like BigQuery to copy the database.

This Markdown-formatted summary provides a structured overview of the project, highlighting its objectives, data handling processes, focus areas, and additional context. It offers a clear and organized view of the information gathered from your recent conversation.

## Citations

- U.S. Environmental Protection Agency. (n.d.). Underground Injection Control Program. Retrieved from https://www.epa.gov/uic

- National Academy of Sciences. (2013). Induced Seismicity Potential in Energy Technologies. The National Academies Press. doi: 10.17226/13355

- International Society of Rock Mechanics and Rock Engineering. (2015). Suggested Methods for Determination of Seismic Velocities. In R. Ulusay (Ed.), The ISRM Suggested Methods for Rock Characterization, Testing and

- Monitoring: 2007-2014 (pp. 151-168). Springer International Publishing. doi: 10.1007/978-3-319-07713-0_7

- Society of Exploration Geophysicists. (2010). SEG Y rev 1 Data Exchange Format. Retrieved from https://seg.org/Publications/SEG-Y-revision-1
  Krischer, L., Megies, T., Barsch, R., Beyreuther, M., Lecocq, T., Caudron, C., & Wassermann, J. (2015). ObsPy: A bridge for seismology into the scientific Python ecosystem. Computers & Geosciences, 81, 190-199. doi: 10.1016/j.cageo.2015.07.017

- U.S. Department of Energy. (n.d.). Carbon Utilization and Storage Atlas. Retrieved from https://netl.doe.gov/projects/carbon-storage-atlas
- U.S. Environmental Protection Agency. (n.d.). Greenhouse Gas Equivalencies Calculator Calculations and References. Retrieved from https://www.epa.gov/energy/greenhouse-gas-equivalencies-calculator-calculations-and-references

- Internal Revenue Service. (n.d.). Section 45Q Credit for Carbon Oxide Sequestration. Retrieved from https://www.irs.gov/pub/irs-drop/rp-20-25.pdf

- U.S. Department of Energy. (n.d.). Enhanced Oil Recovery. Retrieved from https://www.energy.gov/eere/fossil/enhanced-oil-recovery
  National Petroleum Council. (2019). Meeting the Dual Challenge: A Roadmap to At-Scale Deployment of Carbon Capture, Use, and Storage. Retrieved from https://www.npc.org/reports/dual-challenge/

- These citations cover various aspects of the project, including EPA regulations, seismic monitoring, data formats, carbon capture and utilization, and enhanced oil recovery techniques.

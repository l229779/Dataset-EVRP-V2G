The instances are formatted as follows:

### For each instance provides:
- **StringId**: a unique identifier
- **i**: total nodes
- **k**: vehicles
- **c**: customers
- **Es**: recharging station
- **cs_0**: energy cost in normal time
- **cs_1**: energy cost in peak time
- **e, l**: time windows
- **s**: service time
- **Q**: Vehicle battery capacity (units of energy available)
- **qV**: Vehicle load capacity (units available for cargo)
- **qC**: demand customers
- **H**: consumption rate (reduction of battery capacity when traveling one unit of distance)
- **RIO**: inverse refueling rate (units of time required to recharge one unit of energy)
- The velocity is assumed to be constant on all arcs, which is required to calculate the travel time from the distance.
- **x, y**: coordinates (distances are assumed to be euclidean)

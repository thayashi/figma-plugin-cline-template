## 02-documentation.md (Project Overview)

### Project Description
A Figma plugin that scans the current selected frames and lists all elements that use direct RGB color values (not design tokens or styles). This helps designers identify hardcoded colors that should be converted to design system semantic colors.

### UI Design
Follow Figma plugin best practice. It should be very simple interaction (KISS).

### Core Features
1. **RGB Color Detection**
Scan all layers for direct RGB color usage.

2. **Color Enumeration**:
List found colors with their hex values and usage count.

3. **Node Navigation**:
Click on color entries to navigate to specific nodes

4. **Export Functionality**: Export color list as JSON/CSV

### User Flow
1. User opens plugin from Figma plugins menu
2. When open the plugin, the plugin nothing will do. 
3. User select a frame 
4. Click the 'Scan' button, then Plugin scans current selected frames and find the nodes using RGB colors, and list the nodes. If user hasn't selected a frame, notify the user to select a frame.
5. User can click to navigate to specific nodes
6. Optional: Export results for further analysis


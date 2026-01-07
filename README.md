#FlowPy Alpha Angle Validation Workflow

1. Create algorhythm to take larger area polygon of Inputs (PRA, FS, DSM), then use the avalanchepaths polygon (with buffer?) to cut each slide path out individually.

2. Use the thalweg of each slide path running up the thalweg until the top of the pass. Use this to then find the slope over that line, calculating a travel path profile for each slide path.

3. Filter occurance data for higher-certainty outputs (Top/Middle/Bottom at first, perhaps more identifiers later). Run each occurance up the slope array to calculate the alpha angle for each occurance. Create histograms for size over alpha angle, wet vs dry, etc.

4. Create algorhythm for running the previously created FlowPy inputs for each avalanchepath polygon over the entire region through FlowPy. Add ability to change forest friction and input alpha angle.

5. Compare calculated alpha angle through flowpy to the occurance alpha angle dataset and create comparison figures.

6. Test different forest frictions and input alpha angles to occurance dataset
# AutoFlowPy
# AutoFlowPy
# AutoFlowPy
# AutoFlowPy

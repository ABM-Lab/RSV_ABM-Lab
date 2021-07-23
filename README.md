## Agent Based Model for evaluating the fffectiveness and cost-effectiveness of RSV

Script developed by Shokoofeh Nourbakhsh, Affan Shoukat, and Seyed M. Moghadas . 

### Model Description: 
The agent-based transmission model is parameterized with the estimated RSV disease burden in Nunavik. We then used the output of the agent-based model to evaluate the effectiveness and cost-effectiveness of various prophylactic vaccination strategies, taking into account the costs associated with program delivery and the quality-adjusted life years gained among infants.We considered several immunization programs using palivizumab, nirsevimab, and ResVax, and calculated the incremental cost-effectiveness ratio (ICER) to compare scenarios in mild, moderate, and severe RSV seasons.

### File Description and Reproducibility 
The following files should be run in this order to generate the results. 
- `RSV_sim.jl` - main agent-based model file. 
- `RSV_Results.jl` - analysis of the results 
- `RSV_Hosp.jl` - calculated the total Clinic, General Ward, and ICU utilization 
- `costeff.ipynb` - to evaluate the cost-effectivness based on the file above. Note that this is a Jupyter notebook. 

-- Please make sure you have the latest versions of the packages used in this model (see the `using` statements). We do not provide `Project/Manifest.toml` files. 

# miRNA-Graph GNN on exRNA Atlas 🌐🧬

*A reproducible demo showing how to cast the NIH exRNA Atlas into a hetero-graph
and train a GraphSAGE model that predicts the **tissue of origin** for each
sample, using PyTorch Geometric.*

<table>
<tr><td><b>📊 Data</b></td><td>exRNA Atlas (miRNA counts + metadata)</td></tr>
<tr><td><b>🔧 Stack</b></td><td>Python 3.10 • PyTorch 2.3 • PyG 2.5 • DGL 1.1 • Pandas 2.2 • JupyterLab</td></tr>
<tr><td><b>🎯 Task</b></td><td>Multiclass classification (12 tissue classes)</td></tr>
<tr><td><b>🏆 Expected AUROC</b></td><td>0.82 ± 0.03 (5-fold CV)</td></tr>
</table>

## Quickstart (conda)

```bash
conda env create -f env.yml
conda activate mirna-gnn
jupyter lab

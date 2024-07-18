
## Lineage markers

```{r}

# Major cells
mouse_major_cells_brian <- list(
    "Granulocyte" = c("G0s2", "S100a9", "S100a8"),
    "Myeloid_cells"	= c("C1qa", "Apoe", "C1qb"),
    "Ductal/cancer_cells" = c("Krt8", "Krt18", "Krt19"),
    "Fibroblast" = c("Dcn", "Col1a2", "Col3a1"),
    "T_cell" = c("Cd3g", "Cd3e", "Nkg7"),
    "Acinar_cells" = c("Try4",	"Try5",	"Klk1"),
    "B_cell" = c("Cd79a", "Cd79b", "Ms4a1"),
    "DC" = c("Cst3", "Ccl17", "H2-Ab1"),
    "pDC" = c("Bst2", "Siglech"),
    "Endothelial" = c("Fabp4", "Flt1", "Emcn"),
    "Plasma_cells" = c("Igkc", "Jchain", "Slpi")
)

# Fibroblasts
mouse_caf_yunhe_and_kathleen <- list(
    "caf1" = c('Col1a1', 'Col2a1', 'Col1a3', 'Col6a1', 'Col6a2', 'Col3a1', 'Col1a2'),
    "icaf1" = c('Cxcl13', 'Il6', 'Cxcl12', 'Cxcl14'),
    "mycaf1" = c('Tgfb1', 'Acta2', 'Tagln'),
    "apcaf1" = c('H2-Ab1', 'H2-Ea', 'H2-Eb1', 'Cd74', 'H2-Eb2', 'H2-Eb3'),
    "iCAF2" = c("Clec3b", "Col14a1", "Ly6c1", "Il6"),
    "myCAF2" = c("Tagln", "Thy1", "Col12a1", "Thbs2"),
    "apCAF2" = c("H2-Ab1", "Cd74", "Saa3", "Slpi"),
    "panCAF2" = c("Col1a2", "Col1a2", "Pdpn", "Dcn")
)

# Immune-related cells (Not needed)
mouse_immune_compartment <- list(
    "Cd4_T_cell" = c("Cd4", "Cd3g", "Shisa5", "Cd52", "Cd3d"),
    "Cd8_T_cell" = c("Cd8a", "Cd8b1", "Cd52", "Thy1"),
    "B_cell_2" = c("Cd79a", "Cd79b", "Ms4a1"),
    "NK_cells_2" = c("Ptprc", "Skap1", "Klrk1", "Nkg7"),
    "Plasma_cells_2" = c("Igkc", "Jchain", "Slpi"),
    "cDC" = c("Cd74", "Arhgap15", "Dock10", "Plbd1", "Pip4k2a"),
    "pDC" = c("Cyth4", "Tyrobp", "Irf8", "Siglech")
)

# Lymphocytes cells
mouse_t_cell_compartment <- list(
    "NK_T_Cells" = c("Cd3d", "Cd3e", "Nkg7", "Klrd1"),
    "CD4p_naive_T_cells" = c("Lef1", "Cd4", "Ccr7"),
    "CD8p_naive_T_cells" = c("Ccr7", "Cd8a", "Cd8b1", "Tcf7"),
    "T_regs" = c("Cd3d", "Cd3e", "Ikzf2", "Foxp3"),
    "CD4p_activated_T_cells" = c("Cd4", "Tcf7", "Cd40lg"),
    "CD8p_effector_T_cells" = c("Cd8a", "Cd8b1", "Gzmk", "Ccl5"),
    "NK_cells" = c("Nkg7", "Klrd1", "Ccl5", "Fcer1g", "Tyrobp"),
    "CD8p_memory_cells" = c("Cd3d", "Cd3e", "Ly6c2", "Sidt1"),
    "Th17_cells" = c("Cd3d", "Cd3e", "Tcf7", "Ikzf2", "Il23r", "Il1r1"),
    "Th2_cells" = c("Ikzf2", "Gata3", "Il1rl1")
)

```

**Note, I left the markers in the README.md inside the main folder. The authors from the original studies suggested the majority of the markers.**

# Topological Edge States in Helical Soft-Matter Lattices

Code repository for the paper:

**"Topological Edge States in Helical Soft-Matter Lattices: Microtubules as a Natural Platform"**
Lucas Pinheiro (2025)

## Requirements
```
pip install numpy scipy matplotlib
```

## Scripts

| Script | Description | Output |
|--------|-------------|--------|
| `ssh_band_structure.py` | Bulk band structure (Fig. 1a) | `fig1a_band_structure.pdf` |
| `ssh_domain_wall.py` | Domain wall state profile (Fig. 1b) | `fig1b_domain_wall.pdf` |
| `lindblad_decay.py` | Coherence decay comparison (Fig. 2) | `fig2_coherence_decay.pdf` |
| `winding_number.py` | Winding number vs t2/t1 | Terminal output |
| `cylindrical_model.py` | Gap survival in 13-PF cylinder | Terminal output (table) |

## Usage

Each script is standalone. Run with:
```
python ssh_band_structure.py
python ssh_domain_wall.py
python lindblad_decay.py
python winding_number.py
python cylindrical_model.py
```

All scripts run in under 5 minutes on a standard laptop.

## License

MIT
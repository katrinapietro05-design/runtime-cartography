# SOVRINT Master Execution Pathways

Author: Katrina Pietroniro™  
System: SOVRINT™

## Universal Python Executor

Use:

    bash scripts/run_py.sh PATH/TO/file.py

Examples:

    bash scripts/run_py.sh AXIOM_PRIME/qlce/engine.py
    bash scripts/run_py.sh THE_LATTICE/engines/E3_IIE/resonance_mapper.py
    bash scripts/run_py.sh THE_LATTICE/engines/E6_CME/manifold_monitor.py
    bash scripts/run_py.sh THE_LATTICE/engines/E7_CVE/bio_oversight.py
    bash scripts/run_py.sh THE_LATTICE/engines/E8_JLE/energy_bridge.py
    bash scripts/run_py.sh THE_LATTICE/engines/transmutation_ledger.py
    bash scripts/run_py.sh CORE_ENGINES/Node_091/logic.py

## Shell Builder Execution

Use:

    bash scripts/SCRIPT_NAME.sh

## Execution Doctrine

- Do not execute unknown files blindly.
- Compile or inspect first when a file writes ledgers or calls shell scripts.
- Use scripts/run_py.sh as the controlled Python execution layer.
- Preserve root: ~/MASTER_SOVEREIGN_LATTICE.

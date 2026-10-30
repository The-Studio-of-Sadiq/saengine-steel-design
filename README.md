# SAEngine steel design

Steel member and connection design, the steel section library, the steel drawing sheets and the steel results panel of SAEngine.

**This repository is a read-only mirror.** The code is developed in [SAEngine](https://github.com/The-Studio-of-Sadiq/SAEngine) and copied here from commit [`2bcc31461e`](https://github.com/The-Studio-of-Sadiq/SAEngine/commit/2bcc31461e8b352dd30bb8fa107e0eb1e774202c) by `scripts/modules/mirror.py`. Every update replaces the whole content, so open issues and pull requests in SAEngine, not here. Once the module interface is stable the module will move here and SAEngine will install it as a package.

The files keep their paths in SAEngine:

- `python/src/saengine/design/steel`
- `python/src/saengine/design/steel_design.py`
- `python/src/saengine/design/steel_proposal.py`
- `python/src/saengine/design/steel_connections.py`
- `python/src/saengine/library/steel_sections.py`
- `python/src/saengine/drawings/sheets/steel.py`
- `python/src/saengine/verification/cases/steel.py`
- `python/tests/test_design_steel.py`
- `python/tests/test_design_steel_connections.py`
- `python/tests/test_design_steel_frame.py`
- `python/tests/test_design_steel_proposal.py`
- `python/tests/test_drawings_steel.py`
- `python/tests/test_steel_integration.py`
- `python/tests/test_steel_sections.py`
- `workbench/src/vs/workbench/contrib/saengineFem/browser/femSteelDesign.ts`
- `workbench/src/vs/workbench/contrib/saengineFem/test/browser/femSteelDesign.test.ts`
- `docs/images/steel-drawings`

Not in this module:

- The steel tables of a design code (BNBC 2020: python/src/saengine/codes/packs/bnbc2020/data/steel.json) belong to the code pack and are published by saengine-design-codes, not here.
- The shared design pipeline that calls steel (design/check.py, design/proposal.py, design/overwrites.py, report/build.py, library/objects.py, drawings/sheets/model.py) stays in the core.

Licence: AGPL-3.0-only (see LICENSE), the same as SAEngine.

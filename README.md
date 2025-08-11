Blueprint to 3D Walkthrough

This project transforms 2D architectural blueprints into immersive 3D models.
It allows users to visualize floor plans as interactive 3D walkthroughs, helping architects, designers, and clients better understand the layout and design before construction begins.

The goal of this project is to provide a realistic representation of building interiors and exteriors directly from 2D blueprint images, making design communication more effective.


Repo Structure


blueprint-to-3d/
│
├── blueprint_processing/       # Python scripts for image & DXF parsing
│   ├── __init__.py
│   ├── detect_walls.py
│   ├── extract_shapes.py
│   ├── utils.py
│
├── blender_scripts/            # Scripts that Blender will run for extrusion
│   ├── __init__.py
│   ├── extrude_walls.py
│   ├── import_blueprint.py
│
├── unity_project/               # Unity project folder (optional Unreal)
│   └── Assets/
│       └── ...
│
├── samples/                     # Sample blueprints & DXF files
│   ├── blueprint1.png
│   ├── blueprint2.dxf
│
├── docs/                        # Notes, guides, and planning docs
│   ├── phase_plan.md
│
├── requirements.txt             # Python dependencies
├── README.md                    # Project overview
└── .gitignore                   # Ignore unwanted files

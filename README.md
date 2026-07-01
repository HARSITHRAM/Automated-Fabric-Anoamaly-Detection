# Automated-Fabric-Anoamaly-Detection
Develop an Automated Fabric Anomaly Detection System that inspects garments during the ironing process and detects defects before the garments are folded.

Process Flow
Wrinkled Garment
        │
        ▼
Feed Conveyor
        │
        ▼
Ironing Roller / Heated Rod
        │
        ▼
📷 Inspection Zone (Camera + Lighting)
        │
        ▼
AI detects defects
        │
        ├── OK → Continue to Folding Machine
        │
        └── DEFECT → Reject / Alarm / Mark garment

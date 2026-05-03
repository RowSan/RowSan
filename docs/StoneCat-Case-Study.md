StoneCat — Warehouse Intelligence System
Technical Business Analysis | System Design | Data Integration

**Problem**
Natural stone wholesale operations relied on fragmented workflows:
	•	ERP systems provided raw stock counts only
	•	Sales reps depended on manual checks, calls, and messaging
	•	Inventory visibility across warehouses was inconsistent
This created delays during client interactions and reduced sales efficiency.

**Solution**
Designed and implemented StoneCat, a warehouse intelligence system that transforms ERP data into a structured, real-time mobile experience.
The system separates:
	•	Automated data ingestion (ERP → database)
	•	Curated operational data (batches, dimensions, locations, media)
This creates a reliable, read-optimised interface for sales and operations.

**System Architecture**
	•	Data Pipeline: ERP CSV → Edge Function → PostgreSQL (upsert with validation)
	•	Data Model: Relational structure linking inventory, warehouse locations, and batch-level slab data
	•	Mobile Layer: React Native interface optimised for real-time access
	•	Access Control: Role-based access (Admin vs Rep) with controlled data visibility

**Core Capabilities**
	•	Real-time inventory visibility across multiple warehouses
	•	Batch-level tracking (dimensions, location, stock context)
	•	Structured data validation during ingestion
	•	Media-to-inventory linking for contextual decision-making
	•	Read-optimised mobile interface for field usage

**Scale**
	•	Processes 1000+ inventory records per sync
	•	Supports multi-warehouse operations
	•	Handles structured and unstructured operational data

**Business Impact**
	•	Reduced dependency on manual stock verification
	•	Improved response time during client interactions
	•	Centralised inventory visibility into a single system
	•	Established a structured data foundation for operations
**
Future Scaling**
	•	CRM layer for customer interaction and sales tracking
	•	Web-based authenticated catalogue for client-facing access
	•	Direct ERP API integration for real-time sync (beyond CSV pipeline)

**Professional Contribution**
	•	Led requirements analysis and system design
	•	Designed data architecture and integration pipeline
	•	Implemented mobile interface and data workflows
	•	Delivered a production-ready system aligned with operational needs
















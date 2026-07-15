# Global Vista Canonical Project Index

**File:** `Global_Vista_Canonical_Project_Index_v1.0.md`  
**Project:** Global Vista  
**Index Version:** 1.0  
**Architecture Baseline:** Version 1.1  
**Status:** Active Canonical Index  
**Last Updated:** July 14, 2026  

---

## 1. Purpose

This document provides the canonical folder structure and master inventory for Global Vista.

It identifies:

- Active files
- Planned files
- Deferred files
- Historical files
- Superseded concepts
- Standards
- Source code
- Components
- Tests
- Release files
- Research material
- Reference dashboards
- Side projects
- Files discussed but not yet created

This index SHALL be updated whenever a canonical file is added, renamed, superseded, archived, or frozen.

---

## 2. Status Key

| Status | Meaning |
|---|---|
| Canonical | Current authoritative file |
| Active | In current development |
| Draft | Written but not frozen |
| Planned | Approved for future creation |
| Deferred | Intentionally postponed |
| Historical | Retained for project history |
| Superseded | Replaced by a newer file |
| Experimental | Test or prototype |
| Reference | Example or supporting material |
| Archived | No longer active |

---

## 3. Recommended Repository Structure

```text
GlobalVista/
├── README.md
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE.md
├── release_index.json
├── Global_Vista_Master_Project_Specification.md
├── Global_Vista_Canonical_Project_Index_v1.0.md
│
├── 00_Project_Governance/
│   ├── Global_Vista_Master_Governance_Standard_v1.0.md
│   ├── Global_Vista_Privacy_and_Personal_Information_Policy_v1.0.md
│   ├── Global_Vista_Copyright_Trademark_and_Licensing_Policy_v1.0.md
│   ├── Global_Vista_AI_Transparency_Standard_v1.0.md
│   ├── Global_Vista_Accessibility_Standard_v1.0.md
│   ├── Global_Vista_Data_Governance_Standard_v1.0.md
│   ├── Global_Vista_Security_Standard_v1.0.md
│   ├── Global_Vista_Release_Governance_Standard_v1.0.md
│   ├── Global_Vista_Incident_Response_Plan_v1.0.md
│   ├── Global_Vista_Third_Party_Risk_Standard_v1.0.md
│   └── Global_Vista_User_Rights_Standard_v1.0.md
│
├── 01_Master_Architecture/
│   ├── Global_Vista_Master_Architecture_v1.1.md
│   ├── Global_Vista_System_Architecture_Diagram_v1.1.md
│   ├── Global_Vista_Platform_Architecture_v1.0.md
│   ├── Global_Vista_Information_Flow_Architecture_v1.0.md
│   ├── Global_Vista_Development_Roadmap_v1.1.md
│   ├── Global_Vista_Version_Strategy_v1.0.md
│   ├── Global_Vista_Project_Recovery_and_Consolidation_Strategy.md
│   └── Global_Vista_Architecture_Decision_Log.md
│
├── 02_Standards/
│   ├── GVDVP/
│   │   ├── Global_Vista_Deterministic_Visualization_Pipeline_GVDVP_v1.1.md
│   │   └── GVDVP_v1.1_Schema.json
│   ├── GVDS/
│   │   ├── Global_Vista_Design_System_GVDS_v1.0.md
│   │   └── GVDS_Design_Tokens.json
│   ├── GVCL/
│   │   └── Global_Vista_Component_Library_GVCL_v1.0.md
│   ├── GVSI/
│   │   └── Global_Vista_Spatial_Interface_GVSI_v1.0.md
│   ├── GVSIL/
│   │   └── Global_Vista_Spatial_Intelligence_Language_GVSIL_v1.0.md
│   ├── GVFS/
│   │   └── Global_Vista_Frame_Standard_GVFS_v1.0.md
│   ├── GVXS/
│   │   └── Global_Vista_Experience_Standards_GVXS_v1.0.md
│   ├── ACS/
│   │   └── Adaptive_Centerpiece_Standard_ACS_v1.0.md
│   ├── GVCES/
│   │   └── Global_Vista_Cinematic_Experience_Standard_GVCES_v1.0.md
│   ├── GVGRS/
│   │   └── Global_Vista_Geospatial_Rendering_Standard_GVGRS_v1.0.md
│   ├── GVCS/
│   │   └── Global_Vista_Compliance_Standard_GVCS_v1.0.md
│   ├── GVIVS/
│   │   ├── Global_Vista_Image_Validation_Standard_GVIVS_v1.0.md
│   │   └── GVIVS_Validation_Rules.json
│   ├── GVIAS/
│   │   └── Global_Vista_Information_Architecture_Standard_GVIAS_v1.0.md
│   └── Future/
│       ├── Global_Vista_Knowledge_Architecture_Standard_GVKAS_v1.0.md
│       └── Global_Vista_3D_4D_Engine_Standard_GV3D_v1.0.md
│
├── 03_Design_Bible/
│   ├── Global_Vista_Design_Bible_Volume_1_Foundations.md
│   ├── Global_Vista_Design_Bible_Volume_2_Spatial_Layout.md
│   ├── Global_Vista_Design_Bible_Volume_3_Color_Light_and_Materials.md
│   ├── Global_Vista_Design_Bible_Volume_4_Typography.md
│   ├── Global_Vista_Design_Bible_Volume_5_Interaction.md
│   ├── Global_Vista_Design_Bible_Volume_6_Cinematic_Composition.md
│   ├── Global_Vista_Design_Bible_Volume_7_Geospatial_Design.md
│   └── Global_Vista_Design_Bible_Volume_8_Accessibility.md
│
├── 04_Product_and_Experience/
│   ├── Global_Vista_Product_Definition.md
│   ├── Global_Vista_Mission_and_Vision.md
│   ├── Global_Vista_Entry_Experience.md
│   ├── Global_Vista_Front_Door_Experience.md
│   ├── Global_Vista_Onboarding_Specification.md
│   ├── Global_Vista_Navigation_Model.md
│   ├── Global_Vista_Essential_Standard_Comprehensive_Modes.md
│   ├── Global_Vista_Pricing_and_Access_Tiers.md
│   ├── Global_Vista_Local_Vista_Product_Specification.md
│   └── Global_Vista_Skylight_Product_Specification.md
│
├── 05_Information_Architecture/
│   ├── Global_Vista_Information_Model_v1.0.md
│   ├── Global_Vista_Ranked_Event_Model_v1.0.md
│   ├── Global_Vista_Source_Model_v1.0.md
│   ├── Global_Vista_Dashboard_Region_Model_v1.0.md
│   ├── Global_Vista_Overview_Tab_Schema_v1.0.json
│   ├── Global_Vista_Pre_Render_Intelligence_Manifest_v1.0.json
│   ├── Global_Vista_Five_Second_Comprehension_Test.md
│   └── Global_Vista_Information_Architecture_Reference_Dashboard_v0.1.md
│
├── 06_Source_Code/
│   ├── App/
│   │   ├── GlobalVistaApp.swift
│   │   ├── GlobalVistaRootView.swift
│   │   └── GlobalVistaSettingsEngine.swift
│   ├── Core/
│   │   ├── GlobalVistaCoreModels.swift
│   │   ├── GlobalVistaEventModels.swift
│   │   ├── GlobalVistaSourceModels.swift
│   │   ├── GlobalVistaGeospatialModels.swift
│   │   ├── GlobalVistaValidationModels.swift
│   │   └── GlobalVistaConfiguration.swift
│   ├── Pipeline/
│   │   ├── GVDVPPipeline.swift
│   │   ├── GVIASLayoutEngine.swift
│   │   ├── ACSCenterpieceSelector.swift
│   │   ├── GVCESSceneComposer.swift
│   │   ├── GVGRSGeospatialRenderer.swift
│   │   ├── GVIVSImageValidator.swift
│   │   └── GVCSComplianceGate.swift
│   ├── Components/
│   │   ├── GV_Component_3DGlassButton_v1.0.swift
│   │   ├── GV_Component_SourceDock_v1.0.swift
│   │   ├── GV_Component_SelectableIntelligenceRow_v1.0.swift
│   │   ├── GVButton.swift
│   │   ├── GVNavigationRail.swift
│   │   ├── GVSignalCard.swift
│   │   ├── GVSourceDock.swift
│   │   ├── GVTimeline.swift
│   │   ├── GVHeatMap.swift
│   │   ├── GVThreatRibbon.swift
│   │   ├── GVEventCard.swift
│   │   ├── GVConfidenceGauge.swift
│   │   └── GVRelationshipGraph.swift
│   ├── Views/
│   │   ├── GlobalVistaOverviewView.swift
│   │   ├── GlobalVistaIntelligenceView.swift
│   │   ├── GlobalVistaAnalyticsView.swift
│   │   ├── GlobalVistaMapsView.swift
│   │   ├── GlobalVistaTimelineView.swift
│   │   └── GlobalVistaReportsView.swift
│   └── Resources/
│       ├── Localization/
│       ├── DesignTokens/
│       ├── Schemas/
│       └── ReferenceData/
│
├── 07_Reference_Dashboards/
│   ├── Global_Warming_Overview_Reference.md
│   ├── Local_Vista_Las_Cruces_El_Paso_Reference.md
│   ├── FIFA_World_Cup_Overview_Reference.md
│   ├── Nebraska_Corn_Overview_Reference.md
│   ├── Ebola_Outbreak_Overview_Reference.md
│   ├── Mars_Popcorn_Concept_Reference.md
│   ├── Southwest_US_Mortality_Assessment_Reference.md
│   ├── Shadow_Blaster_Galaxy_Reference.md
│   └── Cyber_Threats_and_Internet_Outages_Reference.md
│
├── 08_Tests/
│   ├── Unit/
│   │   ├── test_gvdvp.py
│   │   ├── test_gvfs.py
│   │   ├── test_acs.py
│   │   ├── test_gvces.py
│   │   ├── test_gvgrs.py
│   │   ├── test_gvcs.py
│   │   ├── test_gvivs.py
│   │   └── test_gvias.py
│   ├── Integration/
│   │   ├── test_image_provider_integration.py
│   │   ├── test_dashboard_render_pipeline.py
│   │   ├── test_source_dock_integration.py
│   │   └── test_geospatial_pipeline.py
│   ├── End_to_End/
│   │   ├── test_las_cruces_overview.py
│   │   ├── test_world_cup_overview.py
│   │   ├── test_nebraska_corn_overview.py
│   │   ├── test_ebola_overview.py
│   │   └── test_mars_popcorn_overview.py
│   ├── Fixtures/
│   │   ├── overview_10_events.json
│   │   ├── source_dock_fixture.json
│   │   ├── geospatial_fixture.json
│   │   └── dashboard_layout_fixture.json
│   └── Baselines/
│       ├── v1.1_freeze_manifest.json
│       └── image_validation_baselines/
│
├── 09_CI_and_Release/
│   ├── clean_release.py
│   ├── validate_release_index.py
│   ├── freeze_baseline.py
│   ├── release_checklist.md
│   ├── versioning_policy.md
│   └── github_actions/
│       ├── test.yml
│       ├── image_validation.yml
│       └── clean_release.yml
│
├── 10_Research_and_References/
│   ├── Academic_Research_and_ScholarGPT_Integration_Framework.md
│   ├── Global_Vista_Source_Authority_Framework.md
│   ├── Global_Vista_News_Density_Methodology.md
│   ├── Global_Vista_Confidence_Scoring_Methodology.md
│   ├── Global_Vista_Geospatial_Research.md
│   ├── Global_Vista_Apple_Vision_Pro_Research.md
│   └── Global_Vista_Competitive_Research.md
│
├── 11_Project_Management/
│   ├── Global_Vista_Development_Journal.md
│   ├── Global_Vista_Decision_Log.md
│   ├── Global_Vista_Bug_Register.md
│   ├── Global_Vista_Risk_Register.md
│   ├── Global_Vista_Test_Register.md
│   ├── Global_Vista_Roadmap.md
│   └── Global_Vista_Backlog.md
│
├── 12_Side_Projects/
│   ├── Feline_Intelligence_Reports/
│   ├── Espresso_Log/
│   ├── SwiftUI_Component_Lab/
│   ├── Local_Vista/
│   └── Skylight/
│
├── 13_Archive/
│   ├── Superseded_Standards/
│   ├── Historical_Layouts/
│   ├── Deprecated_Prompts/
│   ├── Failed_Render_References/
│   └── Previous_Release_Baselines/
│
└── 14_Output/
    ├── Renders/
    ├── Reports/
    ├── Exports/
    └── Validation_Reports/
```

---

## 4. Root Files

| File | Status | Purpose |
|---|---|---|
| `README.md` | Canonical | Repository introduction and current version |
| `CHANGELOG.md` | Planned | Version changes |
| `CONTRIBUTING.md` | Planned | Contribution rules |
| `LICENSE.md` | Planned | Licensing notice |
| `release_index.json` | Canonical | Release bundle and version metadata |
| `Global_Vista_Master_Project_Specification.md` | Canonical | Top-level system specification |
| `Global_Vista_Canonical_Project_Index_v1.0.md` | Canonical | Master file and folder inventory |

---

## 5. Mandatory Standards

| Standard | File | Current Status |
|---|---|---|
| GVDVP | `Global_Vista_Deterministic_Visualization_Pipeline_GVDVP_v1.1.md` | Canonical |
| GVDS | `Global_Vista_Design_System_GVDS_v1.0.md` | Active |
| GVCL | `Global_Vista_Component_Library_GVCL_v1.0.md` | Active |
| GVSI | `Global_Vista_Spatial_Interface_GVSI_v1.0.md` | Active |
| GVSIL | `Global_Vista_Spatial_Intelligence_Language_GVSIL_v1.0.md` | Active |
| GVFS | `Global_Vista_Frame_Standard_GVFS_v1.0.md` | Active |
| GVXS | `Global_Vista_Experience_Standards_GVXS_v1.0.md` | Active |
| ACS | `Adaptive_Centerpiece_Standard_ACS_v1.0.md` | Active; needs correction |
| GVCES | `Global_Vista_Cinematic_Experience_Standard_GVCES_v1.0.md` | Draft; freeze priority |
| GVGRS | `Global_Vista_Geospatial_Rendering_Standard_GVGRS_v1.0.md` | Mandatory |
| GVCS | `Global_Vista_Compliance_Standard_GVCS_v1.0.md` | Mandatory final gate |
| GVIVS | `Global_Vista_Image_Validation_Standard_GVIVS_v1.0.md` | Planned / high priority |
| GVIAS | `Global_Vista_Information_Architecture_Standard_GVIAS_v1.0.md` | Deferred to Version 2 |
| GVKAS | `Global_Vista_Knowledge_Architecture_Standard_GVKAS_v1.0.md` | Future Version 3 |
| GV3-D | `Global_Vista_3D_4D_Engine_Standard_GV3D_v1.0.md` | Future |

---

## 6. Files Explicitly Discussed

The following files or document classes have been explicitly discussed in project work.

### Core architecture

- `README.md`
- `release_index.json`
- `Global_Vista_Master_Project_Specification.md`
- `Global_Vista_Canonical_Project_Index_v1.0.md`
- `Global_Vista_Master_Architecture_v1.1.md`
- `Global_Vista_Development_Roadmap_v1.1.md`
- `Global_Vista_Project_Recovery_and_Consolidation_Strategy.md`
- `Global_Vista_Architecture_Decision_Log.md`

### Standards

- `Global_Vista_Deterministic_Visualization_Pipeline_GVDVP_v1.1.md`
- `Global_Vista_Design_System_GVDS_v1.0.md`
- `Global_Vista_Component_Library_GVCL_v1.0.md`
- `Global_Vista_Spatial_Interface_GVSI_v1.0.md`
- `Global_Vista_Spatial_Intelligence_Language_GVSIL_v1.0.md`
- `Global_Vista_Frame_Standard_GVFS_v1.0.md`
- `Global_Vista_Experience_Standards_GVXS_v1.0.md`
- `Adaptive_Centerpiece_Standard_ACS_v1.0.md`
- `Global_Vista_Cinematic_Experience_Standard_GVCES_v1.0.md`
- `Global_Vista_Geospatial_Rendering_Standard_GVGRS_v1.0.md`
- `Global_Vista_Compliance_Standard_GVCS_v1.0.md`
- `Global_Vista_Image_Validation_Standard_GVIVS_v1.0.md`
- `Global_Vista_Information_Architecture_Standard_GVIAS_v1.0.md`

### Swift and component files

- `GlobalVistaCoreModels.swift`
- `GlobalVistaSettingsEngine.swift`
- `GV_Component_3DGlassButton_v1.0.swift`
- `GV_Component_SourceDock_v1.0.swift`
- `GV_Component_SelectableIntelligenceRow_v1.0.swift`
- `GVButton.swift`
- `GVNavigationRail.swift`
- `GVSignalCard.swift`
- `GVSourceDock.swift`
- `GVTimeline.swift`
- `GVHeatMap.swift`
- `GVThreatRibbon.swift`
- `GVEventCard.swift`
- `GVConfidenceGauge.swift`
- `GVRelationshipGraph.swift`

### Product and experience files

- `Global_Vista_Product_Definition.md`
- `Global_Vista_Mission_and_Vision.md`
- `Global_Vista_Entry_Experience.md`
- `Global_Vista_Front_Door_Experience.md`
- `Global_Vista_Onboarding_Specification.md`
- `Global_Vista_Navigation_Model.md`
- `Global_Vista_Local_Vista_Product_Specification.md`
- `Global_Vista_Skylight_Product_Specification.md`

### Research and supporting files

- `Academic_Research_and_ScholarGPT_Integration_Framework.md`
- `Global_Vista_Development_Journal.md`
- `Global_Vista_Source_Authority_Framework.md`
- `Global_Vista_News_Density_Methodology.md`
- `Global_Vista_Confidence_Scoring_Methodology.md`
- `Global_Vista_Apple_Vision_Pro_Research.md`

---

## 7. Frequently Forgotten or Overshadowed Files

These items have been discussed or implied but can easily disappear behind the newer standards.

| File | Why it matters |
|---|---|
| `Global_Vista_Entry_Experience.md` | Defines the first user encounter |
| `Global_Vista_Front_Door_Experience.md` | Separates welcome, onboarding, and operational entry |
| `Global_Vista_Project_Recovery_and_Consolidation_Strategy.md` | Prevents fragmented repository history |
| `Global_Vista_Architecture_Decision_Log.md` | Records why major decisions were made |
| `Global_Vista_Development_Journal.md` | Preserves chronological development history |
| `Academic_Research_and_ScholarGPT_Integration_Framework.md` | Supports future research workflows |
| `Global_Vista_Source_Authority_Framework.md` | Establishes source ranking and authority |
| `Global_Vista_News_Density_Methodology.md` | Defines a permanent Global Vista metric |
| `Global_Vista_Confidence_Scoring_Methodology.md` | Prevents vague confidence labels |
| `Global_Vista_Five_Second_Comprehension_Test.md` | Converts “understand quickly” into a test |
| `Global_Vista_Bug_Register.md` | Tracks recurring defects systematically |
| `Global_Vista_Risk_Register.md` | Tracks technical, legal, product, and release risks |
| `Global_Vista_Test_Register.md` | Connects standards to test coverage |
| `Global_Vista_Information_Architecture_Reference_Dashboard_v0.1.md` | Front-end test bed for GVIAS |
| `Global_Vista_Privacy_and_Personal_Information_Policy_v1.0.md` | Protects private individuals |
| `Global_Vista_Release_Governance_Standard_v1.0.md` | Defines freeze and release rules |

---

## 8. Reference Dashboards and Test Subjects

These subjects have served as useful reference or failure-detection cases.

| Reference | Purpose |
|---|---|
| Global Warming Overview | Core 3-D globe and Top 10 baseline |
| Las Cruces / El Paso Local Vista | Local and regional layout |
| FIFA World Cup Overview | Tournament, schedule, bracket, trophy, globe |
| Nebraska Corn Overview | Agriculture and state-level geospatial testing |
| Ebola Outbreak Overview | Health intelligence and event ranking |
| Mars Popcorn Concept | Scientific-concept and unusual-subject testing |
| Southwest U.S. Mortality Assessment | Analytical reference |
| Shadow Blaster Galaxy | Cinematic spatial reference |
| Cyber Threats and Internet Outages | Technology and network intelligence |

---

## 9. Known Recurring Bugs

The Bug Register SHOULD include at least:

1. Portrait render instead of 16:9 landscape
2. Missing Source Dock
3. Incorrect number of ranked events
4. Event #1 not glowing
5. Flat or weak 3-D composition
6. Missing or incorrect centerpiece
7. Blurry, tiny, overlapping, or cropped text
8. Missing continuous frame
9. Unsafe margins
10. Missing dashboard sections
11. Incorrect geospatial composition
12. Prompt-to-render drift
13. Trophy or hero-object placement errors
14. Generic source icons replacing named sources
15. Placeholder graphics
16. Missing title
17. Cropped panels
18. Incomplete image validation
19. Version mismatch in support documents
20. Release index inconsistency

---

## 10. Testing Inventory

### Current known baseline

- Python tests: 37/37 passing

### Required test files

- `test_gvdvp.py`
- `test_gvfs.py`
- `test_acs.py`
- `test_gvces.py`
- `test_gvgrs.py`
- `test_gvcs.py`
- `test_gvivs.py`
- `test_gvias.py`
- `test_image_provider_integration.py`
- `test_dashboard_render_pipeline.py`
- `test_source_dock_integration.py`
- `test_geospatial_pipeline.py`
- `test_las_cruces_overview.py`
- `test_world_cup_overview.py`
- `test_nebraska_corn_overview.py`
- `test_ebola_overview.py`
- `test_mars_popcorn_overview.py`

---

## 11. Active Side Projects

| Project | Status |
|---|---|
| Feline Intelligence Reports | Active side project |
| Espresso Log | Active side project |
| SwiftUI Component Lab | Active |
| Local Vista micro-dashboard | Active |
| Skylight AVP air-traffic concept | Backlog / future |
| Widget | Back burner |

---

## 12. Deferred Version 2 Files

- `Global_Vista_Information_Architecture_Standard_GVIAS_v1.0.md`
- `Global_Vista_Overview_Tab_Schema_v1.0.json`
- `Global_Vista_Pre_Render_Intelligence_Manifest_v1.0.json`
- `Global_Vista_Five_Second_Comprehension_Test.md`
- `Global_Vista_Dashboard_Type_Catalog_v1.0.md`
- `Global_Vista_Information_Completeness_Rules_v1.0.md`
- `Global_Vista_Off_the_Wall_News_Specification_v1.0.md`

---

## 13. Future Version 3 Files

- `Global_Vista_Knowledge_Architecture_Standard_GVKAS_v1.0.md`
- `Global_Vista_Knowledge_Graph_Schema_v1.0.json`
- `Global_Vista_Entity_Relationship_Model_v1.0.md`
- `Global_Vista_Neural_Intelligence_Engine_Specification_v1.0.md`
- `Global_Vista_Causal_Inference_Model_v1.0.md`
- `Global_Vista_Temporal_Relationship_Model_v1.0.md`

---

## 14. Recommended Creation Order

### Now

1. `Global_Vista_Bug_Register.md`
2. `Global_Vista_Test_Register.md`
3. `Global_Vista_Information_Architecture_Reference_Dashboard_v0.1.md`
4. `Global_Vista_Cinematic_Experience_Standard_GVCES_v1.0.md`
5. `Adaptive_Centerpiece_Standard_ACS_v1.0.md`
6. `Global_Vista_Image_Validation_Standard_GVIVS_v1.0.md`
7. Image-provider integration tests
8. End-to-end tests
9. Clean-release CI

### Later

1. GVIAS files
2. Information manifests
3. Dashboard schemas
4. Knowledge architecture
5. Neural intelligence engine

---

## 15. Naming Rules

Use:

```text
Global_Vista_<Descriptive_Name>_v<major>.<minor>.<extension>
```

Exceptions:

- `README.md`
- `CHANGELOG.md`
- `CONTRIBUTING.md`
- `LICENSE.md`
- `release_index.json`
- Swift type names that follow Swift conventions

Component pattern:

```text
GV_Component_<ComponentName>_v1.0.swift
```

Test pattern:

```text
test_<system_or_feature>.py
```

---

## 16. Canonical Maintenance Rules

1. Every canonical file SHALL appear in this index.
2. Every file SHALL declare status and version.
3. Superseded files SHALL move to `13_Archive/`.
4. Historical files SHALL not remain mixed with active files.
5. Release files SHALL agree on version.
6. Test coverage SHALL be linked to standards.
7. New standards SHALL identify their pipeline position.
8. Deferred files SHALL not be treated as mandatory.
9. Version 2 GVIAS rules SHALL not block Version 1.1 stabilization.
10. The index SHALL be updated at every freeze.

---

## 17. Current Project Position

The project is presently in:

> **Global Vista Version 1.1 Stabilization Phase**

Primary effort:

- Front-end reliability
- Repeat bug elimination
- GVCES freeze
- ACS correction
- GVIVS construction
- Integration testing
- End-to-end testing
- Clean-release automation

GVIAS remains approved in concept but deferred to Version 2.

---

## 18. Canonical Principle

> One repository, one authoritative structure, one known-good baseline.

The purpose of this index is to prevent Global Vista from becoming a glowing maze of duplicated files, contradictory versions, and forgotten decisions. Software naturally attempts this transformation when unsupervised.

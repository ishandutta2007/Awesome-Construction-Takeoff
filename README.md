# Awesome-Construction-Takeoff

Markdown
## Top Construction Takeoff Ecosystem


**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Construction Takeoff, Quantity Takeoff, Digital Plan Measurement, CAD/BIM Quantification, AI Takeoff & Preconstruction*  
**Last updated: August 2026**


This repository tracks notable **SaaS/Hosted Platforms** and **open-source projects** for **Construction Takeoff**. These tools help contractors, estimators, subcontractors, quantity surveyors, architects, engineers, and preconstruction teams measure quantities from construction drawings, PDFs, CAD/BIM models, images, and digital plans.


**Examples** include PlanSwift, STACK, Bluebeam Revu, On-Screen Takeoff, ConstructConnect Takeoff, CostX, Cubit, Buildxact, FastDUCT, Active Takeoff, Togal.AI, Autodesk Takeoff, and Estimating Edge.


Modern construction takeoff increasingly combines **PDF measurement + CAD/BIM quantity extraction + AI computer vision + automated symbol detection + OCR + plan comparison + markup + estimating + BOQ generation + cost databases**.


**Open-source emphasis**: This repository is heavily expanded with open-source projects and building blocks for constructing custom takeoff systems. The open-source ecosystem is smaller than the commercial construction-takeoff market, but projects such as **OpenTakeoff** and **OpenConstructionERP** now provide particularly relevant starting points for self-hosted PDF/CAD/BIM takeoff and estimating. OpenTakeoff is an Apache-2.0 open-source PDF takeoff engine with area, linear, count and related measurement capabilities, while OpenConstructionERP combines BOQ, PDF/CAD/BIM takeoff, estimating and construction workflows under an open-source license. 


Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or GitHub repositories.


## Table of Contents


- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Additional Strong Open-Source Options](#additional-strong-open-source-options)
- [Open-Source Construction Takeoff Stack](#open-source-construction-takeoff-stack)
- [Construction Takeoff Building Blocks](#construction-takeoff-building-blocks)
- [Important Construction Takeoff Concepts](#important-construction-takeoff-concepts)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)


## SaaS/Hosted Platforms

| Platform | Description | Pricing (Starting Tier) | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[PlanSwift](https://www.planswift.com/)** | Construction takeoff and estimating platform for digital plan measurement, assemblies, and Takeoff Boost AI features. | $1,749 / year per license | 14-day free trial (full desktop version access, no credit card required) |
| **[STACK](https://www.stackct.com/)** | Cloud-based construction takeoff and estimating platform with digital plan measurement, collaboration, and bid management. | $249 / user / month (Premium tier, billed annually; Pro tier starts at $299 / user / month) | Free forever plan (up to 2 concurrent projects, 10 takeoffs per project, 7-day project lifespan) |
| **[Bluebeam Revu](https://www.bluebeam.com/)** | PDF markup, drawing management, and takeoff software with Studio collaboration and measurement tools. | $260 / user / year (Basics tier; Core tier starts at $330 / user / year) | 14-day free trial (full access to Max tier, Studio, desktop, web, mobile; no credit card required) |
| **[On-Screen Takeoff](https://www.constructconnect.com/products/on-screen-takeoff)** | 2D takeoff and estimating software by ConstructConnect for area, linear, and count quantity takeoffs. | ~$1,850 / year per single-user license | 14-day free trial (full desktop OST evaluation; free single-page web preview for Takeoff Boost AI) |
| **[ConstructConnect Takeoff](https://www.constructconnect.com/products/takeoff)** | Cloud-integrated takeoff tool within ConstructConnect's preconstruction network for plan measurement. | ~$1,000 / month (starter plans / preconstruction suite subscriptions with annual agreement) | Guided proof-of-value demo on user's own plans; free single-page evaluation on web via Takeoff Boost |
| **[CostX](https://www.rib-software.com/en/products/rib-costx)** | Professional 2D/3D BIM quantity takeoff, estimating, and cost-planning platform by RIB Software. | ~$4,500 per license (starting professional tier investment) | Free 12-month educational license for verified students; free live customized guided product demo |
| **[Cubit](https://www.buildsoft.com.au/cubit)** | Natural estimating and digital takeoff software with interactive sheet links and BOQ generation by Buildsoft. | $167 AUD + GST / user / month (Cubit Estimating Standard, billed annually) | 14-day free trial (full access to Cubit Estimating software features) |
| **[Buildxact](https://www.buildxact.com/)** | Cloud takeoff, estimating, and project management platform designed for residential builders and trades. | $199 / month (Foundation tier; $0/month on Go plan) | Free "Go" plan (includes 5 complimentary AI estimating and proposal credits); 14-day free trial of full platform |
| **[FastDUCT](https://www.fastduct.com/)** | Specialized HVAC ductwork, sheet-metal, and mechanical estimating and takeoff software by FastEST. | $250 / month (standalone lease option; or $4,995 one-time purchase) | 60-day money-back guarantee period for risk-free evaluation; free live guided demo |
| **[Active Takeoff](https://www.activetakeoff.com/)** | Fast digital plan measurement and quantity takeoff tool supporting PDF, CAD, and image plans. | $59 / user / month (or $698 - $898 one-time perpetual license) | 14-day free trial (full software functionality, no credit card required) |
| **[Togal.AI](https://www.togal.ai/)** | AI-powered automated takeoff software detecting rooms, walls, objects, areas, and drawing schedules. | $199 / user / month (Essential plan; Growth plan starts at $299 / user / month billed annually) | 7-day free trial via eTakeoff Dimension integration with unlimited drawings; free custom live demo |
| **[Autodesk Takeoff](https://construction.autodesk.com/products/autodesk-takeoff/)** | Cloud-based 2D sheet and 3D BIM model takeoff solution within Autodesk Construction Cloud (ACC). | $1,290 / user / year (~$108 / month billed annually) | 30-day free trial (full 2D and 3D model quantification and sheet access, no credit card required) |
| **[The EDGE](https://www.estimatingedge.com/)** | Commercial trade takeoff and estimating software by Foundation Software for roofing, drywall, and finishes. | ~$12,000 upfront implementation & license package (~$300+/month seat equivalent) | Free customized live demo with company blueprints; 1-month trial for EDGE On Site mobile tracking app |  
Recommended Open-Source Combinations

Basic PDF Takeoff

OpenTakeoff + PDF.js + Shapely

Useful for building a lightweight self-hosted digital takeoff application.

AI PDF Takeoff

OpenTakeoff + OpenCV + PaddleOCR + SAM 2 + Grounding DINO

Useful for experimenting with automated room, symbol, text, and geometry extraction from construction drawings.

CAD Takeoff

ezdxf + LibreDWG + Shapely + OpenTakeoff

Useful for extracting and measuring geometry from 2D CAD drawings.

BIM Quantity Takeoff

IfcOpenShell + xeokit + PostgreSQL + OpenConstructionERP

Useful for extracting quantities from IFC/BIM models and connecting them with BOQ and estimating workflows.

AI Construction Drawing Analyzer

PyMuPDF + PaddleOCR + OpenCV + Grounding DINO + SAM 2

Useful for building a custom system that detects drawing elements, reads labels and dimensions, and generates structured construction information.

Full Open-Source Construction Takeoff Platform

OpenTakeoff + PDF.js + PyMuPDF + OpenCV + PaddleOCR + IfcOpenShell + ezdxf + Shapely + OpenConstructionERP + PostgreSQL + DuckDB

This combination covers PDF takeoff, drawing processing, OCR, computer vision, CAD/BIM extraction, geometry, quantities, BOQ, estimating, data storage, and analytics.

Construction Takeoff Building Blocks
Drawing Input

PDF Takeoff

Digital Plan Takeoff

Scanned Plan Takeoff

Blueprint Takeoff

Construction Drawing Takeoff

Plan Set Processing

Multi-Sheet Processing

Drawing Revision Management

Drawing Version Control

CAD Takeoff

BIM Takeoff

IFC Takeoff

DWG Takeoff

DXF Takeoff

RVT Takeoff

Image Takeoff

Aerial Takeoff

Point Cloud Takeoff

Measurement

Area Measurement

Linear Measurement

Count Measurement

Volume Measurement

Surface Area Measurement

Perimeter Measurement

Length Measurement

Height Measurement

Distance Measurement

Polygon Measurement

Polyline Measurement

Radius Measurement

Diameter Measurement

Angle Measurement

Slope Measurement

Elevation Measurement

Room Measurement

Floor Area Measurement

Wall Area Measurement

Roof Area Measurement

Quantity Takeoff

Quantity Takeoff

Digital Takeoff

Manual Takeoff

Automated Takeoff

AI Takeoff

Computer Vision Takeoff

BIM Quantity Takeoff

CAD Quantity Takeoff

PDF Quantity Takeoff

Material Takeoff

Equipment Takeoff

Labor Takeoff

Fixture Takeoff

Door Takeoff

Window Takeoff

Wall Takeoff

Flooring Takeoff

Roofing Takeoff

Concrete Takeoff

Steel Takeoff

Lumber Takeoff

Drywall Takeoff

Painting Takeoff

Electrical Takeoff

Plumbing Takeoff

HVAC Takeoff

Mechanical Takeoff

Sitework Takeoff

Earthwork Takeoff

Landscape Takeoff

AI Takeoff

AI Construction Takeoff

AI Quantity Takeoff

AI Plan Measurement

AI Drawing Analysis

AI Blueprint Analysis

AI Construction Vision

Computer Vision Takeoff

Automated Room Detection

Automated Wall Detection

Automated Door Detection

Automated Window Detection

Automated Fixture Detection

Automated Symbol Detection

Automated Dimension Detection

Automated Schedule Extraction

AI OCR

Vision-Language Models

Construction Vision Models

Plan Understanding

Drawing Understanding

Semantic Segmentation

Instance Segmentation

Object Detection

Layout Detection

Symbol Recognition

Scale & Calibration

Drawing Scale

Automatic Scale Detection

Scale Calibration

Dimension Calibration

Known-Dimension Calibration

Architectural Scale

Engineering Scale

Metric Scale

Imperial Scale

Multi-Scale Plan Sets

Per-Sheet Scale

Coordinate Calibration

Georeferencing

Geometry

Polygon Geometry

Polyline Geometry

Line Detection

Wall Centerline Detection

Boundary Detection

Intersection Detection

Polygon Union

Polygon Difference

Polygon Offset

Buffering

Deduction Areas

Cutouts

Openings

Geometric Constraints

Snap-to-Endpoint

Snap-to-Line

Snap-to-Intersection

Orthogonal Drawing

Angle Lock

BIM / CAD

BIM Quantity Takeoff

IFC Quantity Takeoff

Revit Quantity Takeoff

DWG Quantity Takeoff

DXF Quantity Takeoff

CAD Geometry Extraction

BIM Element Extraction

BIM Property Extraction

BIM Classification

BIM Object Detection

Model-Based Takeoff

5D BIM

4D BIM

OpenBIM

IFC

BCF

COBie

BIM Data Exchange

Estimating

Construction Estimating

Cost Estimating

Quantity-Based Estimating

Assembly-Based Estimating

Unit Cost Estimating

Material Pricing

Labor Pricing

Equipment Pricing

Subcontractor Pricing

Cost Database

Regional Cost Database

Historical Cost Database

Productivity Rates

Labor Productivity

Material Waste

Markup

Overhead

Profit

Contingency

Bid Estimate

BOQ / Tendering

Bill of Quantities

BOQ

Schedule of Quantities

Quantity Schedule

Bid Schedule

Tender Documents

Bid Package

Scope Breakdown

Cost Codes

CSI MasterFormat

NRM

UniFormat

Assembly Codes

Work Breakdown Structure

Cost Breakdown Structure

Revision Management

Drawing Revision

Plan Revision

Revision Comparison

Drawing Overlay

Addendum Tracking

Change Detection

Quantity Delta

Revision Cloud

Version Comparison

Historical Takeoff

Bid Revision

Change Order Takeoff

Markup

PDF Markup

Drawing Markup

Color-Coded Takeoff

Takeoff Overlay

Annotations

Callouts

Text Markup

Dimension Markup

Revision Clouds

Punch Markups

Custom Symbols

Markup Templates

Markup Libraries

Collaboration

Cloud Takeoff

Collaborative Takeoff

Multi-User Takeoff

Concurrent Takeoff

Takeoff Sharing

Bid Collaboration

Estimator Collaboration

Subcontractor Collaboration

Plan Sharing

Drawing Permissions

Project Permissions

Reporting

Takeoff Reports

Quantity Reports

Material Reports

Labor Reports

Cost Reports

BOQ Reports

Bid Reports

Marked-Up Plans

CSV Export

Excel Export

JSON Export

PDF Export

Quantity Summary

By-Sheet Quantities

By-Trade Quantities

By-Assembly Quantities

Specialty Takeoff

Roofing Takeoff

Flooring Takeoff

Drywall Takeoff

Concrete Takeoff

Masonry Takeoff

Painting Takeoff

Electrical Takeoff

Plumbing Takeoff

HVAC Takeoff

Ductwork Takeoff

Mechanical Takeoff

Fire Protection Takeoff

Insulation Takeoff

Glazing Takeoff

Doors & Windows Takeoff

Steel Takeoff

Structural Takeoff

Sitework Takeoff

Earthwork Takeoff

Landscaping Takeoff

Civil Takeoff

Open-Source Construction Takeoff

Open-Source Takeoff

Open-Source Quantity Takeoff

Open-Source PDF Takeoff

Open-Source CAD Takeoff

Open-Source BIM Takeoff

Open-Source AI Takeoff

Open-Source Construction Estimating

Open-Source BOQ

Open-Source Cost Estimation

Open-Source Plan Measurement

Open-Source Blueprint Analysis

Open-Source Construction Computer Vision

Open-Source Construction OCR

Open-Source BIM Quantity Extraction

Open-Source CAD Geometry Extraction

Self-Hosted Takeoff

Self-Hosted Estimating

Self-Hosted Construction Software

Offline Takeoff

Local AI Takeoff

AI Agents & Construction Takeoff

AI Takeoff Agents

Construction Estimating Agents

AI Quantity Surveyor

AI Estimator

AI Blueprint Agent

AI Plan Agent

AI Construction Copilot

Agentic Takeoff

MCP Takeoff

AI Measurement

AI Quantity Extraction

AI BOQ Generation

AI Cost Estimation

AI Drawing QA

AI Revision Detection

AI Bid Preparation

Human-in-the-Loop Takeoff

Agentic Construction Estimating

Important Construction Takeoff Concepts

Construction Takeoff

Quantity Takeoff

Digital Takeoff

Material Takeoff

Quantity Surveying

Construction Estimating

Cost Estimating

Digital Blueprint

Digital Construction Drawing

Plan Measurement

PDF Takeoff

CAD Takeoff

BIM Takeoff

AI Takeoff

Automated Takeoff

Computer Vision Takeoff

Construction Computer Vision

Blueprint Computer Vision

Drawing Understanding

Plan Understanding

Construction OCR

Construction Document AI

AI Estimator

AI Quantity Surveyor

AI Construction Copilot

AI Takeoff Agent

Agentic Takeoff

MCP Takeoff

Room Detection

Wall Detection

Door Detection

Window Detection

Fixture Detection

Symbol Detection

Dimension Detection

Schedule Extraction

Automatic Scale Detection

Scale Calibration

Area Measurement

Linear Measurement

Count Measurement

Volume Measurement

Surface Area Measurement

Perimeter Measurement

Polygon Measurement

Line Measurement

Distance Measurement

CAD Geometry

BIM Geometry

IFC

DWG

DXF

RVT

BIM Quantity Extraction

BIM Object Extraction

BIM Property Extraction

5D BIM

4D BIM

OpenBIM

Open IFC

CAD-to-Quantity

BIM-to-Quantity

PDF-to-Quantity

Image-to-Quantity

Drawing-to-BOQ

Drawing-to-Estimate

Drawing-to-Cost

Quantity-to-Cost

Quantity-to-BOQ

Material Takeoff

Labor Takeoff

Equipment Takeoff

Assembly Takeoff

Trade Takeoff

Specialty Contractor Takeoff

Roofing Takeoff

Flooring Takeoff

Concrete Takeoff

Drywall Takeoff

Electrical Takeoff

Plumbing Takeoff

HVAC Takeoff

Ductwork Takeoff

Mechanical Takeoff

Steel Takeoff

Structural Takeoff

Civil Takeoff

Earthwork Takeoff

Sitework Takeoff

Painting Takeoff

Masonry Takeoff

Insulation Takeoff

Glazing Takeoff

Doors & Windows Takeoff

Fire Protection Takeoff

Landscape Takeoff

BOQ

Bill of Quantities

Schedule of Quantities

Cost Database

Material Database

Labor Database

Unit Cost

Assembly Cost

Productivity Rate

Material Waste

Labor Productivity

Markup

Overhead

Profit

Contingency

Bid Estimate

Tender Estimate

Preconstruction

Bid Preparation

Bid Management

Estimating Workflow

Drawing Revision

Plan Revision

Addendum

Drawing Comparison

Quantity Delta

Revision Tracking

Overlay Comparison

Change Detection

Markup

Drawing Annotation

Color-Coded Takeoff

Takeoff Overlay

Digital Markup

Cloud Takeoff

Collaborative Takeoff

Multi-User Takeoff

Takeoff QA

Estimate QA

Quantity Validation

Human-in-the-Loop

Takeoff Audit Trail

Takeoff Provenance

Automated Quantity Validation

Construction Data Extraction

Construction Document Intelligence

Construction AI

AEC AI

Open-Source Takeoff

Open-Source Estimating

Open-Source BIM Takeoff

Open-Source CAD Takeoff

Open-Source AI Takeoff

Self-Hosted Takeoff

Self-Hosted Estimating

Offline Takeoff

Local AI Takeoff

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow the existing format).

Include: name, official link or GitHub repository, 1–2 sentence description, and whether it is SaaS/hosted or open-source.

For open-source projects, identify the primary capability — takeoff, PDF processing, CAD, BIM, computer vision, OCR, geometry, estimating, BOQ, or construction ERP.

Clearly distinguish open-source, source-available, open-core, research projects, libraries, and commercial hosted products.

Verify the current license before adding an open-source entry.

Prefer actively maintained repositories with meaningful documentation and recent development.

Do not describe a PDF library, CAD parser, BIM library, or computer-vision framework as a complete PlanSwift/STACK replacement unless it actually provides construction takeoff functionality.

For takeoff-specific entries, prioritize functionality such as drawing measurement, quantity extraction, scale calibration, automated detection, CAD/BIM extraction, takeoff markup, BOQ generation, or estimating integration.

Submit a PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Commercial construction takeoff platforms frequently combine proprietary drawing viewers, measurement engines, AI detection, estimating databases, collaboration, markup, and bid-management features.

The open-source ecosystem is significantly more fragmented than the commercial construction-takeoff market.

Some open-source projects listed here are complete takeoff applications, while others are PDF processors, CAD libraries, BIM frameworks, computer-vision models, OCR engines, geometry libraries, or construction ERP systems that can be combined into a custom takeoff platform.

OpenTakeoff is a dedicated open-source takeoff application, whereas projects such as OpenCV, Tesseract, IfcOpenShell, ezdxf, Shapely, and PDF.js are building blocks rather than complete commercial takeoff replacements.

Always verify the current license, maintenance status, documentation, dependencies, security posture, and deployment model before adopting an open-source project.

AI-generated quantities should be independently reviewed before being used for contractual bids, procurement, construction pricing, or safety-critical decisions.

Construction drawings can contain confidential project information. Self-hosted deployments should use appropriate authentication, access control, encryption, backups, network isolation, and audit logging.

Quantity takeoff methodologies vary by trade, geography, contract type, measurement standard, and estimating practice.

Construction estimates should be reviewed by qualified estimators and relevant construction professionals before being used for commercial bids.

Made for estimators, quantity surveyors, general contractors, subcontractors, architects, engineers, preconstruction teams, BIM professionals, construction technologists, and developers.
Let's make construction takeoff more open, automated, AI-powered, interoperable, auditable, accurate, and accessible.

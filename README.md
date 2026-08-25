# Virtual Technical Conference Platform

## Problem Statement

A technical symposium portal that manages double-blind paper reviews, generates conflict-free multi-track presentation schedules, and provides real-time upvoted Q&A queues during conference sessions.

## Project Overview

The **Virtual Technical Conference Platform** is designed to simplify the management of technical conferences. The system supports paper submission and double-blind review, reviewer assignment, conference scheduling, and real-time interaction through session-based Q&A.

## Actors

* **Conference Author** – Submits manuscripts and views paper status.
* **Reviewer** – Reviews assigned manuscripts.
* **Track Chair** – Manages reviewers, conflicts of interest, conference schedules, and sessions.
* **Conference Participant** – Views sessions, asks questions, and upvotes questions.

## Deliverables

### 1. Requirements Table

Contains:

* 5 Functional Requirements (FR-001 to FR-005)
* 2 Non-Functional Requirements (NFR-001 to NFR-002)
* Priority
* Acceptance Criteria
* Rationale

### 2. UML Use-Case Diagram

The diagram represents the actors and major interactions with the Virtual Technical Conference Platform.

It includes:

* Conference Author
* Reviewer
* Track Chair
* Conference Participant
* «include» relationship
* «extend» relationship

### 3. Use-Case Flow Specification

The selected core use case is **Generate Conference Schedule**.

The specification includes:

* Preconditions
* Postconditions
* Main Success Scenario
* Alternate Flow

## Repository Structure

Virtual-Technical-Conference/
│
├── requirements.pdf
│
├── use-case.png
│
├── Use-Case-Flow.pdf
│
└── README.md


## Key Features

* Double-blind manuscript anonymization
* Conflict-free reviewer assignment
* Multi-track conference schedule generation
* Room capacity and speaker availability management
* Live session-based Q&A
* Question upvoting and prioritization

## Conclusion

The proposed system provides a structured platform for managing the major activities of a virtual technical conference, from manuscript submission and review to scheduling and real-time participant interaction.

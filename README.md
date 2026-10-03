# DOJ OMS

### DOJRP Operations Management System

**A centralized Windows operations workspace built for DOJRP law enforcement members.**

DOJ OMS brings the tools commonly used during DOJRP law enforcement operations into one standalone desktop application.

Rather than keeping patrol tracking, Career Progression, department resources, CAD access, Penal Code references, report preparation, statistics, and officer information scattered across multiple locations, DOJ OMS provides a single workspace designed around the active officer and their department.

> **Current Release:** v1.5.0  
> **Platform:** Windows 10 / Windows 11  
> **Release Channel:** Stable  
> **Supported Departments:** BCSO & SAHP

---

# Download DOJ OMS

The latest stable version of DOJ OMS is available through the **Releases** section of this repository.

### Installation

1. Open the latest DOJ OMS release.
2. Download the latest `DOJ_OMS_Setup` installer.
3. Run the installer.
4. Complete the Windows installation prompts.
5. Launch **DOJ OMS**.
6. Complete the initial identity setup.
7. Create or select your Officer Profile.

Existing users can install newer versions directly over their current installation. Supported locally stored profile, patrol, statistics, Career Progression, and application data are preserved during normal upgrades.

DOJ OMS also includes an integrated update system for detecting future releases.

---

# What is DOJ OMS?

DOJ OMS is designed to function as an operational companion for DOJRP law enforcement members.

The application adapts around the user's **Officer Profile and department**, allowing one installation to support officers with different assignments, ranks, departments, patrol histories, and career records.

Current functionality includes:

- Multi-department Officer Profiles
- Patrol session tracking
- Department and subdivision assignment tracking
- Patrol history
- Patrol statistics
- BCSO & SAHP Career Progression
- Rank History
- Promotion and demotion tracking
- Training and certification tracking
- Department patrol-log integration
- Automatic patrol-log timezone handling
- Department-specific resource libraries
- Quick Resources
- DOJRP CAD access
- Local Penal Code references
- Report Builder
- Automatic OFFENCE(S) synchronization
- DOJRP member verification
- Discord Rich Presence
- Integrated application updates
- Support Center & Help Center
- Development Board

The goal is simple: **reduce the number of separate resources an officer needs to manage while providing a cleaner workspace for day-to-day DOJRP operations.**

---

# Supported Departments

## Blaine County Sheriff's Office

DOJ OMS provides full operational and Career Progression support for the **Blaine County Sheriff's Office (BCSO)**.

Supported BCSO assignments include:

- General Patrol
- Warrant Services Unit — WSU
- Wildlife Rangers — WLR
- Criminal Investigations Division — CID
- Traffic Enforcement Division — TED
- Canine / K9

BCSO Officer Profiles automatically receive the appropriate department resources, patrol options, Quick Resources, Report Builder presentation, patrol-log formatting, and Career Progression system.

---

## San Andreas Highway Patrol

DOJ OMS provides full operational and Career Progression support for the **San Andreas Highway Patrol (SAHP)**.

Supported SAHP assignments include:

- BACO
- BSO - ISU
- BSO - K9
- BTE - DUI-E
- BTE - MBU
- BTE - CVE
- BTE - MRU

SAHP integration includes department-specific ranks, auxiliary ranks, patrol functionality, resources, Quick Resources, Report Builder presentation, patrol-log formatting, and Career Progression.

Additional department integrations can be incorporated as DOJ OMS continues to expand.

---

# Operations Dashboard

The Dashboard serves as the primary operational landing point after selecting an Officer Profile.

From the Dashboard, officers can quickly review their current profile and patrol status while accessing commonly used operational tools and department-specific resources.

Quick Resources automatically adapt to the active Officer Profile's department.

![DOJ OMS Operations Dashboard](screenshots/dashboard.png)

---

# Officer Profiles

DOJ OMS supports **multiple Officer Profiles** within the same installation.

Each profile can maintain its own:

- Department
- Name and unit number
- Badge Number / Web ID
- Rank
- Time zone
- Patrol history
- Patrol statistics
- Career Progression record
- Rank History
- Training and certification information

Switching profiles allows DOJ OMS to automatically adapt supported areas of the application to that officer.

Department-specific resources, patrol assignments, Report Builder information, Career Progression, and other supported functionality change according to the active profile.

Career information remains isolated to the individual Officer Profile. Multiple BCSO or SAHP profiles can therefore maintain completely independent career and patrol records within the same installation.

---

# Career Progression

DOJ OMS v1.5.0 introduces the **Career Progression** system for BCSO and SAHP Officer Profiles.

Career Progression provides a personal workspace for tracking objective department progression requirements alongside the officer's existing patrol activity.

Depending on the department and current rank, DOJ OMS can track information including:

- Current rank
- Next rank
- Rank effective date
- Time in grade
- Promotion cycles
- Monthly patrol activity
- Promotion-specific patrol requirements
- Department training
- Certifications
- Career qualifications
- Learning Domains
- Rank History

Career Progression uses patrol activity already recorded within DOJ OMS when evaluating supported patrol-hour requirements.

Each Officer Profile maintains its own independent Career Progression record.

![DOJ OMS Career Progression](screenshots/career-progression.PNG)

### Rank History

Career Progression includes a dedicated **Rank History** for maintaining the officer's career timeline.

Members can:

- Review previous ranks
- Review promotion dates
- View time spent in each rank
- Backfill previous promotions
- Correct historical career information
- Maintain the actual effective date of each rank

When an existing Officer Profile's rank changes, DOJ OMS can detect the change and offer to record it within Career Progression.

The member can provide the actual effective date of the promotion or demotion before the change is added to Rank History.

Career Progression is a personal tracking tool. DOJ OMS does **not** grant or authorize department promotions.

---

# BCSO Career Progression

BCSO Career Progression supports department-specific progression for Full-Time and Reserve personnel.

Supported tracking includes:

- Calendar-based promotion cycles
- Rank-specific patrol requirements
- Time in grade
- Continuing Education
- BCSO Explorer Program
- FTA
- FTO
- SiT + DA Training
- Applicable trainer certifications
- Historical promotion tracking

DOJ OMS evaluates the objective requirements available to the application and displays **ALL TRACKED REQUIREMENTS COMPLETE** when those requirements have been satisfied.

Final promotion decisions remain with the appropriate department leadership.

---

# SAHP Career Progression

SAHP Career Progression supports both the **Full-Time Trooper** and **Auxiliary Trooper** career paths.

Supported tracking includes:

- Time in grade
- Monthly activity requirements
- Promotion-specific patrol-hour requirements
- Chain of Command patrol requirements
- BPS Learning Domains
- BPS Instructor qualifications
- FTO requirements
- SAHP Corporal Process
- BPS Leadership Examination
- Investigation requirements
- Applicable extracurricular requirements

### BPS Learning Domains

SAHP Career Progression tracks all five BPS Learning Domains:

1. Use of Force
2. High Risk Stops & Vehicular Pursuits
3. Medical Procedures and First Aid
4. Vehicle & Traffic Management
5. Legal Training

Each Learning Domain can independently track both **Certification** and **Instructor Certification** where applicable.

---

# Member Verification

DOJ OMS includes a member verification system for DOJ members-only application material.

Users provide their DOJRP identity information during initial setup, including their name and website profile.

Verification information is used to determine access to protected DOJ member resources.

Access can reflect verification states such as:

- Pending
- Approved
- Denied
- Revoked

Verification is designed around DOJRP membership access.

---

# Patrol Management

DOJ OMS provides real-time patrol session tracking directly from the desktop application.

Officers can:

- Start a patrol
- Pause a patrol
- Resume a patrol
- Change assignments during a patrol
- End a patrol

DOJ OMS independently tracks time spent within supported assignments while maintaining the total duration of the patrol.

Available assignments automatically change according to the active Officer Profile's department.

![DOJ OMS Patrol Management](screenshots/patrol.png)

---

# Patrol Log Integration

DOJ OMS helps streamline department patrol-log submissions.

Supported department integrations can automatically prepare applicable patrol information based on the completed session.

Timezone information is also automatically formatted according to the active Officer Profile and department.

BCSO Patrol Logs use the appropriate timezone abbreviation for the patrol date, while SAHP Patrol Logs use the applicable UTC offset.

Officers should review generated patrol-log information for accuracy and add any required information that cannot be determined automatically, such as training or other special patrol activity.

Patrol-log functionality is designed to reduce repetitive entry while keeping the officer responsible for reviewing the final submission.

---

# Patrol History

Completed patrol sessions are maintained within the active Officer Profile's local patrol history.

Patrol History provides a centralized location for reviewing previous sessions and associated patrol information.

Because patrol history is associated with individual Officer Profiles, users with multiple profiles can maintain separate operational histories within the same DOJ OMS installation.

![DOJ OMS Patrol History](screenshots/history.png)

---

# Patrol Statistics

DOJ OMS automatically calculates statistics using locally stored patrol history.

The Statistics interface provides information such as:

- Total patrol time
- Total completed patrols
- Current-month patrol time
- Current-month patrol count
- Assignment and subdivision time
- Assignment activity percentages
- Patrol-log submission information

Statistics can be viewed across supported periods such as **All Time** and **This Month**.

Statistics remain associated with the Officer Profile responsible for the patrol activity.

![DOJ OMS Patrol Statistics](screenshots/statistics.png)

---

# Department Resources

The Resources module provides organized access to operational material for the active Officer Profile's department.

Instead of maintaining a large collection of bookmarks or repeatedly searching department resources, supported documents and forms can be accessed directly through DOJ OMS.

Resources are organized into department and subdivision-specific sections.

### BCSO

Resources are available for the department and supported areas including:

- WSU
- WLR
- CID
- TED
- K9

### SAHP

Resources are organized across:

- Department Links & Forms
- BACO
- BSO
- BTE

These areas contain applicable documents, forms, training material, operational references, certification information, and subdivision resources.

External resources open through the user's default browser.

---

# Quick Resources

Frequently used department material is available directly from the Dashboard through **Quick Resources**.

Quick Resources automatically change according to the active Officer Profile.

For example, SAHP Quick Resources provide direct access to commonly used material including:

- Standard Operating Procedures
- Policy Memos
- Patrol Zone Map
- Vehicle and Uniform Structure

This allows commonly referenced material to be reached without navigating through the complete Resources library.

---

# DOJRP CAD Access

DOJ OMS provides quick access to the official DOJRP Computer Aided Dispatch system from within the operational workspace.

This reduces the need to separately locate commonly used DOJRP services while working through the application.

![DOJ OMS CAD Access](screenshots/cad.png)

---

# Penal Code Reference

DOJ OMS includes a local Penal Code reference system.

The application does **not** copy or redistribute the official DOJRP Penal Code database.

Instead, officers can maintain local reference entries for information they are authorized to retain or open the official DOJRP Penal Code resource through DOJ OMS.

Local Penal Code information can also be used by supported features such as the Report Builder.

![DOJ OMS Penal Code Reference](screenshots/penal-code.png)

---

# Report Builder

The **Report Builder** provides a modern workspace for preparing standardized information before transferring it into DOJRP reporting systems.

Currently supported report types include:

- Citation Report
- Arrest Report
- Incident Report

Selecting a report type automatically adjusts the applicable report-form heading while maintaining a consistent workspace.

The Report Builder provides:

- Department-specific presentation
- Active Officer Profile information
- Rank-based Issuing Official information
- Badge Number / Web ID integration
- Incident postal and location information
- Local Penal Code charge searching
- Manual charge entry
- Multiple removable charges
- Automatic OFFENCE(S) synchronization
- Standardized narrative preparation
- Individual CAD transfer controls

When entering charges, DOJ OMS can automatically display matches from the officer's **local Penal Code references**.

Charges not contained within the local database can still be entered manually.

Selected charges automatically synchronize with **OFFENCE(S)** within Narrative Format. Adding or removing charges updates the applicable narrative value without requiring the officer to manually re-enter the offences.

Prepared information can then be copied for transfer into the appropriate DOJRP system.

The Report Builder automatically adapts officer information and department presentation according to the active Officer Profile.

![DOJ OMS Report Builder](screenshots/citation-builder.png)

---

# Discord Rich Presence

DOJ OMS includes optional **Discord Rich Presence** integration.

When enabled, Discord can display information associated with DOJ OMS activity, including the active Officer Profile and patrol state.

During active patrols, Rich Presence can reflect information such as:

- Active assignment
- On-duty status
- Patrol activity timing

Pause, Resume, and End Patrol states automatically update supported Discord presence information.

Privacy controls for Discord Rich Presence are available through Settings.

Discord availability is **not required** for normal DOJ OMS operation.

---

# Settings

Application configuration is centralized within the DOJ OMS Settings interface.

Settings provide access to supported options including:

- Officer Profile management
- Profile switching
- General application preferences
- Startup behavior
- Appearance and interface scaling
- Discord Rich Presence preferences
- Update management
- Application information

This separates operational functions from application configuration while keeping commonly changed preferences in one location.

---

# Support Center

DOJ OMS includes an integrated Support Center for application assistance, feedback, and development information.

The Support Center provides access to:

- Help Center
- Frequently Asked Questions
- Submit Request
- Development Board
- Manual update checking
- Application support information

The Help Center has been updated alongside v1.5.0 to reflect current functionality including Officer Profiles, patrol tracking, Statistics, Career Progression, Report Builder, updates, and support.

![DOJ OMS Support Center](screenshots/support-center.PNG)

---

# Automatic Updates

DOJ OMS includes a built-in update system.

The application checks the official DOJ OMS distribution channel for newer releases and can notify users when an update becomes available.

Users can also manually use **Check for Updates** from within the Support Center.

Existing installations can then be upgraded without requiring users to continually monitor the repository for new versions.

---

# Local Data

DOJ OMS is designed primarily around local application storage.

Supported information such as:

- Officer Profiles
- Patrol history
- Assignment timing
- Patrol statistics
- Career Progression
- Rank History
- Training and certification records
- Application preferences

is maintained locally unless the user explicitly uses functionality that submits information through an integrated external service.

---

# System Requirements

**Operating System:** Windows 10 or Windows 11  
**Internet:** Required for online DOJRP resources, verification, external services, and update checking  
**Installation:** Standard Windows installation  
**Discord:** Optional

---

# Getting Started

### 1. Download

Download the latest stable DOJ OMS installer from **Releases**.

### 2. Install

Run the installer and complete the Windows installation process.

### 3. Verify

Complete the initial DOJRP identity information required by the application.

### 4. Create an Officer Profile

Configure your department, name/unit number, Badge Number / Web ID, rank, timezone, and other supported profile information.

### 5. Start Operating

Use the Dashboard to access patrol functionality, Career Progression, department resources, reporting tools, CAD, Penal Code references, and other supported DOJ OMS features.

---

# Current Version

**DOJ OMS v1.5.0 — Stable**

v1.5.0 provides operational and Career Progression support for:

**Blaine County Sheriff's Office**  
**San Andreas Highway Patrol**

The v1.5.0 release introduces Career Progression alongside improvements to Statistics, Report Builder, timezone handling, profile management, and the Help Center.

DOJ OMS remains under active development, with additional functionality and department support planned for future releases.

---

# Development

DOJ OMS began as a patrol-management utility and has expanded into a broader operations workspace for DOJRP law enforcement members.

Development is focused on improving everyday usability, consolidating commonly used operational resources, expanding department-specific functionality, and reducing repetitive work where practical.

Future releases will continue expanding the platform while maintaining compatibility with existing Officer Profiles and locally stored operational information.

Feedback, bug reports, and feature suggestions are encouraged.

---

# Support

For assistance with DOJ OMS, bug reports, feature requests, or other support needs, use the application's **Support Center**.

---

### DOJRP Operations Management System

**One workspace. Your department. Your patrol. Your career.**

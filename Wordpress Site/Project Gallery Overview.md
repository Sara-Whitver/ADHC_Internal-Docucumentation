# Project Overview
## [Alabama Digital Humanities Center Project Gallery](https://adhc.lib.ua.edu/gallery)
The Alabama Digital Humanities Center (ADHC) Project Gallery serves as a centralized showcase of digital scholarship, research initiatives, and collaborative projects developed by faculty, students, and staff at the University of Alabama. The gallery highlights diverse methodologies and interdisciplinary topics across the humanities, providing public access to ongoing and completed digital projects.

---

## Gallery Layout & Filtering
The project gallery is structured as a responsive post grid showcasing each project's featured image, title, and a brief excerpt. Visitors can easily navigate and filter the collection using custom dropdown menus located in the sidebar. 

The filtering system is powered by three core taxonomies implemented via **ACF Pro (Advanced Custom Fields Pro)**[cite: 2]:
- **Discipline:** Categorizes projects by their academic field or department (e.g., History, English, Anthropology).
- **Research Method(s):** Highlights the digital tools, techniques, or methodological approaches utilized (e.g., Text Analysis, GIS/Mapping, Digital Archiving).
- **Topic(s):** Identifies the thematic focus or subject matter of the project.

---

## Individual Project Page Structure
Each individual project page follows a standardized, two-column layout designed to present comprehensive project details clearly and professionally:

### Main Content Area (Left Column)
- **Project Title:** Prominently displayed at the top of the page.
- **Description:** A narrative overview explaining the project's background, goals, and significance.
- **Featured Image:** A primary visual representation or banner associated with the project.
- **Supported By:** Institutional acknowledgment, displaying supporting entities such as the Alabama Digital Humanities Center logo and branding.

### Sidebar Metadata (Right Column)
Powered by custom fields and taxonomies, the sidebar organizes key administrative and academic details:
- **Project Status:** Indicates the current stage of the project (e.g., In Development, Completed, Active).
- **Project Owner(s):** The primary researchers, faculty leads, or creators responsible for the project.
- **Contributor(s):** Collaborators, student assistants, or partner organizations who contributed to the work.
- **Discipline:** The associated academic taxonomy term(s).
- **Research Method(s):** The methodologies applied within the project.
- **Topic(s):** The primary subject classifications.
- **Suggested Citation:** A formatted bibliographic citation for the project, paired with a **Copy to Clipboard** utility icon allowing users to easily copy the citation text with a single click.

---

## Plugins & Technologies Used
The project gallery and its underlying architecture rely on three key plugins:
1. **YMC Filter for Post Grid and Filters:** Powers the dynamic post grid display and the interactive sidebar dropdown filters for seamless browsing[cite: 2].
2. **ACF Pro (Advanced Custom Fields Pro):** Manages custom metadata fields, project owner/contributor details, and the custom taxonomies (Discipline, Research Method(s), Topic(s)).
3. **Copy to Clipboard Icon:** Enables the interactive clipboard copying functionality for the Suggested Citation block on project pages.
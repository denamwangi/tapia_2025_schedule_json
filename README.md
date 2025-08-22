# Tapia 2025 Conference Schedule - JSON Data Format

This repository contains the schedule data for the [Tapia 2025 Conference](https://tapiaconference.cmd-it.org/attend/schedule/) in JSON format. The Tapia Conference is a premier event celebrating diversity in computing, organized by CMD-IT (Center for Minorities and People with Disabilities in Information Technology).

## Data Source

The schedule data was scraped from the official Tapia 2025 Conference website and represents the complete program spanning from September 9-13, 2025, held in Austin, Texas.

## JSON Structure

The JSON file contains the following top-level structure:

```json
{
  "scraped_at": "2025-08-22T16:54:27.758166",
  "source": "example_table_html.txt",
  "total_items": 69,
  "schedule_items": [...]
}
```

### Metadata Fields

- **`scraped_at`**: ISO 8601 timestamp when the data was collected
- **`source`**: Source file used for data extraction
- **`total_items`**: Total number of schedule items in the conference
- **`schedule_items`**: Array containing all conference sessions and events

### Schedule Item Structure

Each item in the `schedule_items` array follows this structure:

```json
{
  "time": "1:00pm - 3:10pm CDT",
  "type": "Panel, Workshop",
  "session_presentation": "CMD-IT Student Professional Development Workshop Panels (Open Invitation)",
  "contributors": "",
  "location": "Texas 1-3",
  "session_id": "sess148",
  "room_id": "room113"
}
```

#### Field Descriptions

- **`time`**: Session duration in Central Daylight Time (CDT)
- **`type`**: Event type(s), which may include multiple types separated by commas
- **`session_presentation`**: Title or description of the session
- **`contributors`**: Presenters, speakers, or organizers (empty string if none specified)
- **`location`**: Room or venue where the session takes place
- **`session_id`**: Unique identifier for the session
- **`room_id`**: Unique identifier for the room/venue

## Event Types

The conference includes various event types:

- **AccessUR2PhD**: Accessibility-focused sessions for underrepresented groups pursuing PhDs
- **Birds of a Feather**: Informal networking and discussion sessions
- **Career Fair**: Job and graduate school opportunities
- **Lightning Talk**: Short presentations (typically 15 minutes)
- **Lunch**: Meal and networking sessions
- **Panel**: Group discussions with multiple speakers
- **Panels & Workshops**: Combined format sessions
- **Plenary**: Keynote and main conference sessions
- **Posters**: Research poster presentations
- **Presentation**: Individual research or topic presentations
- **Reception**: Social and networking events
- **Snack Break**: Refreshment breaks
- **STARS**: Special events for STARS program participants
- **Tech Talk**: Industry technology presentations
- **Workshop**: Interactive learning sessions

## Conference Venues

The conference is held at the Austin Convention Center with the following main areas:

- **Texas Ballroom**: Main plenary sessions and large gatherings
- **Texas 1-6**: Conference rooms for various session types
- **San Antonio 1-6**: Workshop and presentation spaces
- **Dallas 1-7**: Additional meeting rooms
- **Longhorn Hall D**: Career fair location
- **Texas Center Prefunction**: Poster sessions and breaks
- **Grapevine A/B**: Special events

## Data Usage

This JSON data can be used for:

- Building conference apps and websites
- Creating personal schedules
- Data analysis and insights
- Integration with calendar applications
- Research on conference programming and diversity initiatives

## Conference Overview

The Tapia 2025 Conference features:
- **69 total sessions** across 5 days
- **Diverse programming** covering AI, cybersecurity, accessibility, and professional development
- **Multiple session formats** to accommodate different learning styles
- **Career development focus** with extensive networking opportunities
- **Commitment to diversity** in computing and technology

## Data Collection

The schedule data was extracted from the official conference website and structured for programmatic access. The data represents the conference schedule as of the scraping date and may be subject to updates.

## License

This data is provided for educational and research purposes. Please refer to the [official Tapia Conference website](https://tapiaconference.cmd-it.org/) for the most current and authoritative information.

## Contact

For questions about the conference schedule, please visit the [official Tapia Conference website](https://tapiaconference.cmd-it.org/attend/schedule/) or contact CMD-IT directly.

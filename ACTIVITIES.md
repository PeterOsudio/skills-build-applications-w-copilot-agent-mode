# OctoFit Tracker Activities

This file documents the activities available in the OctoFit Tracker application.

## Current Activities

### Manga Maniacs
- **Description**: Explore the fantastic stories of the most interesting characters from Japanese Manga (graphic novels).
- **Schedule**: Tuesdays at 7pm
- **Max Attendance**: 15 people
- **Category**: Reading & Literature
- **Status**: Active

## Activity Data

Activity information is stored in `activities.json` and will be imported into the MongoDB database when the application is set up.

## Adding New Activities

When adding new activities, ensure the following fields are included:
- `id`: Unique identifier
- `name`: Activity name
- `description`: Detailed description of the activity
- `schedule`: When the activity takes place
- `maxAttendance`: Maximum number of participants
- `category`: Activity category
- `active`: Whether the activity is currently active (true/false)

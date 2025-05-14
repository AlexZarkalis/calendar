# Calendar Application - Java

A Java calendar application with GUI for managing appointments and tasks, supporting iCalendar (.ics) format.

## Features
- Create and manage calendar events (appointments and tasks)
- Load and save calendars in standard .ics format
- Automatic 10-minute reminders for upcoming events
- Sort and filter events by various criteria

### Event Management
- **Appointments**:
  - Set start time and duration
  - Add titles and descriptions
- **Tasks**:
  - Set deadlines
  - Track completion status (complete/incomplete)
  - Filter overdue tasks

### Multiple Views
- Day/week/month views
- Past events view
- Task-specific views:
  - Incomplete tasks (before deadline)
  - Overdue tasks

### Prerequisites
- Java 8 or later
- Maven (for dependency management)

### Usage
Clone the repository:
```
git clone https://github.com/yourusername/calendar-app.git
```

Install maven using:

```
mvn clean install
```

Compile using:

```
mvn compile
```

Create a jar using:

```
mvn package
```

Run main using:

```
java -jar ./target/Calendar-1.0-SNAPSHOT.jar
```

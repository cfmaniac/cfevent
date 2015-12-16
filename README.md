# cfevent
This ColdFusion Component package allows you to use an object interface to generate shareable calendar events.
## Purpose
This component is intended to simplify the creation of ICS files, Google Calendar event creation links, and Yahoo! Calendar event creation links. Future development may allow  the ability to import ICS files, import Google Calendar event creation links, import Yahoo! Calendar event creation links, and use ICS files to update existing a cfevent component representing a previous revision of the same event.
## History

## Package Components
This component package defines four components: `cfevent`, `cfevent.alarm`, `cfevent.attendee`, and `cfevent.recurrence`.
### `cfevent`
This is the primary component for creating an event. It supports the specification of most properties available via RFC 5545, such as the unique identifier, sequence, timestamp, start time, end time, subject, location, and description.
### `cfevent.alarm`
This component can be created by the `cfevent` component and added to it for inclusion when exporting. It supports most properties available via RFC 5545.
### `cfevent.attendee`
This component can be created by the `cfevent` component and added to it for inclusion when exporting. While it is not a separate component in RFC 5545, the complexity associated with attendees encourages the creation of a separate interface.
### `cfevent.recurrence`
This component can be created by the `cfevent` component and added to it for inclusion when exporting. While it is not a separate component in RFC 5545, the complexity associated with attendees encourages the creation of a separate interface.
## Usage

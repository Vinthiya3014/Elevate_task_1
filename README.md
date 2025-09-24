
# DOMAIN : HOSTEL MANAGEMENT 
# ENTITIES
**Student**:
Stores information about students staying in the hostel.

**Hostel**:
Represents a hostel building (could be multiple hostels).

**Room**:
Represents rooms inside a hostel.

**Warden**:
Staff member responsible for managing a hostel.

**Allocation**:
Records which student is allocated to which room (bridge table between Student and Room).

**Payment**:
Tracks hostel fee payments made by students.

**Complaint**:
Stores complaints or maintenance requests by students.
#
# RELATIONSHIPS
**Hostel – Warden**

One-to-One (1:1): Each hostel is managed by one warden. A warden manages one hostel.

**Hostel – Room**

One-to-Many (1:N): One hostel can have many rooms, but each room belongs to one hostel.

**Room – Student**

Many-to-Many (M:N): A room can have many students (shared rooms).


**Student – Payment**

One-to-Many (1:N): One student can make many payments, but each payment belongs to one student.

**Student – Complaint**

One-to-Many (1:N): One student can raise many complaints, but each complaint belongs to one student.

**Room – Complaint**

One-to-Many (1:N): A room can have many complaints, but each complaint is linked to one room.
#
# SCREENSHOT OF THE TABLES
<img width="1259" height="437" alt="image" src="https://github.com/user-attachments/assets/62a9d96e-5635-48d5-b413-832d149fb5da" />

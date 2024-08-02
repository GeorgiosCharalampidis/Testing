### Activity vs Job

#### Activity
An **Activity** represents a specific action or task that a transporter (e.g., a lift) performs. Activities are typically associated with a particular state or operation that the transporter must execute. Examples of activities include moving to a location, checking a location, or storing an item.

#### Job
A **Job** represents a higher-level task or a sequence of activities that need to be completed. Jobs are typically more complex and may involve multiple activities to achieve a specific goal. For example, a job might involve moving a container from one location to another, which would include several activities like picking up the container, transporting it, and then placing it at the destination.

### Normal vs Partial Path

#### Normal Path
A normal path is a fully calculated path that allows a transporter to move from its current position to its final destination without any interruptions or need for intermediate adjustments. This path is typically calculated when there are no blocking shuttles or when all blocking shuttles can be deported (moved out of the way).

#### Partial Path
A partial path, on the other hand, is a path that is calculated when a normal path cannot be fully determined due to the presence of blocking shuttles that cannot be deported immediately. The partial path allows the transporter to move as far as possible towards its destination, with the expectation that the blocking shuttles may become deportable in the near future, allowing the transporter to continue its journey.

# CSP---Heuristics

Task 1:
We have five planes: A, B, C, D, and E and two runways: international and domestic. We would like to
schedule a time slot and runway for each aircraft to either land or take off. We have four time slots: {1, 2,
3, 4} for each runway, during which you can schedule a landing or take off of a plane. We must find an
assignment that meets the given constraints.
Variables = [A, B, C, D, E]
Domain = {Di: [1, 2, 3, 4]}
Constraints = adjacent Planes must have different timeslots
e.g., A ≠ B ≠ C ≠ D ≠ E
Following are the constraints description in detail:
• Plane A has lost an engine and must land in time slot 1.
• Plane B is running low on fuel but can last until at most time slot 2.
• Plane D can only arrive at the airport to land during or after time slot 3.
• Plane D must land before plane C takes off because some passengers must transfer from D to C.
• No two aircraft can reserve the same time slot for the same runway
• Planes A, B, and C cater to international flights and can only use the international runway.
• Planes D and E cater to domestic flights and can only use the domestic runway.

![image](https://github.com/rohit546/CSP---Heuristics/assets/100420859/9a4f5dd9-78a5-46be-a5ee-ee036f567154)

Apply the heuristics; minimum-remaining-values (MRV), degree heuristic (DH), and least-
constraining-value (LCV) accordingly for computational analysis

• Display the Solution
• Time Complexity


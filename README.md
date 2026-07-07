# Customer Segmentation

# THEATRICAL BOX OFFICE SEGMENTATION REPORT: FROZEN

Methodology: Chi-Square Automatic Interaction Detector (CHAID) Decision Tree

Core Framework: Directed Feature Steering (Three-Way Demographic Root Split)

Target Variable (Y): Theatrical Movie Ticket Purchase Only

Baseline Market Conversion: 12.0%

🪵 Strategic Rationale: The Three-Way Root Node Split for Cinema Traffic

To optimize pure theatrical box office revenue and theater seat capacity, the tree initiates with a Three-Way Root Node Split (Male / Female / Others).

In the film industry, this phenomenon is tracked using a metric called audience composition data (often managed by companies like National Research Group or Comscore).

When a major family animated feature hits theaters, the baseline purchasing trajectories for male and female buyers look entirely different from day one because they are driven by two completely different buying mechanics: primary demand vs. derived utility.

Here is how that breaks down in the real movie business:

1. The Female Trajectory: Primary Demand & Early Adoption
For a family animation film (especially one with female leads like Frozen), the female demographic represents Primary Demand.

Day One Behavior: The female baseline trajectory spikes immediately on opening weekend. This group contains the organic core fans, teen and young adult enthusiasts, and the "primary household planners" (mothers, aunts, grandmothers).

The Ticket Buying Mechanic: They are buying tickets because they personally want to see the artistic craft, hear the music, or experience the story, or because they are the default coordinators for family weekend plans. Their affinity is direct and self-sustaining.

2. The Male Trajectory: Derived Utility & The "Chaperone Factor"
For this specific genre, the general male baseline trajectory on day one starts much lower because it is almost entirely driven by Derived Utility (buying a ticket as a means to an end, rather than out of direct personal fandom).

The Chaperone & Partner Factor: A significant portion of men do not buy a ticket to a family animation on opening night for themselves. They enter the box office pipeline later, or as a secondary action: either as a dad chaperoning a daughter, or a partner on a date night.

The Statistical Contrast: Because the general male pool includes a massive number of single or non-parent males who have zero interest in a family cartoon, the overall male baseline conversion is mathematically dragged down on day one.

Why this matters to Hollywood Media Buyers

Because these baseline trajectories are so different, studios never run a single, unified ad campaign. They split their budget immediately based on these trajectories:

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/89e45d04-cdfd-47d0-b3c0-bdb2eb246172" />

Instead of wasting money trying to market a family animated movie to all men equally, your model immediately bypasses the low-converting general male baseline and hunts straight for the conditions that turn a man into a buyer: having a daughter and preferring premium formats (IMAX).

From Demographic Core to Behavioral Precision

Step 1: The Root Split (Gender Baseline)

We deliberately force Gender as our absolute root node split. Why? Because in theatrical distribution, male and female purchasing behaviors for a major family animation feature follow entirely different baseline trajectories from day one."

Female Baseline (16% Conv): Starts with a higher native affinity. It represents the immediate, cultural default audience for this specific film asset.

Male Baseline (8% Conv): Starts lower. Men generally do not buy tickets to this specific animated feature for independent consumption; their purchase behavior is almost entirely utility-driven (chaperoning or dating).

Step 2: Expanding to Household Dynamics (The Passenger)
"Once the tree establishes the gender baselines, the algorithm applies the first behavioral filter: Household Structure. Specifically, the presence of a Daughter aged 4–12."

For Mothers (S2A): This creates a Mass Scale effect. The combination of Female + Daughter captures the broad market default. Because the baseline population is so massive, the group's conversion rate flattens out to a highly stable, high-volume 38%. They are our Volume Locomotive.

For Fathers (S2B): This creates a Utility Trigger. A father enters the target market specifically because he is chaperoning his daughter. This instantly multiplies his baseline probability, lifting the male node out of the low 8% zone.

Step 3: Layering the Final Criteria (Format & Spending Behavior)
"The final differentiator—the one that explains why the Father node mathematically edges out the Mother node in pure conversion density—is the Experience Premium Filter."

Mothers (S2A) -> Mass Coordination: Mothers prioritize logistics, group dynamics (booking for playdates, birthday parties, or school friends), and timing (matinees). They buy the most tickets, but across all standard screen formats.

Fathers (S2B) -> The Premium Event: The tree isolates a highly specific micro-segment of fathers who strongly agree with the statement: "I willingly pay extra for premium cinema formats (IMAX/AVX/VIP)."

For this specific micro-segment, the cinema trip is treated as a premium, high-production "event afternoon." This intense intentionality concentrates the node, driving their conversion density up to 45%. They are our Margin Snipers.

🌲 Hierarchical Feature Split Matrix (The Pure Cinema Tree)

<img width="600" height="285" alt="image" src="https://github.com/user-attachments/assets/4a35913e-aa1c-4662-80cd-5308a784033c" />

## Shouldn't mothers buying tickets for their daughters be our absolute highest converting group?

The intuition is entirely correct. Mothers driving daughters to the cinema is our absolute volume locomotive. They fill the most physical seats in the theater.However, from a predictive modeling standpoint, the CHAID tree exposes a fascinating distinction between Mass Scale versus High-Format Efficiency.

1. The Mother Node (Segment 2A): Mass Scale & VolumeThe Data Behavior: Because the sample size for mothers is so large ($N=680$), it naturally captures the entire broad market. This includes everyone from hyper-enthusiastic fans to casual moviegoers who only buy cheap matinee tickets last-minute.The Metric: This pulls the group's average conversion rate to a very strong 38%. They don't have the absolute highest percentage density, but because their baseline population is massive, they generate the highest total volume of ticket sales in our database.The Budget Strategy: We allocate 25% of the budget here to fuel mass parent-centric social media channels and local community networks to maintain our baseline box office momentum.

2. The Father Node (Segment 2B): High-Margin PrecisionThe Data Behavior: This group is significantly smaller ($N=480$). In a decision tree, when a father explicitly screens into the segment by agreeing that he "willingly pays extra for premium cinema formats (IMAX/AVX/VIP)", he becomes a highly qualified, high-intent buyer.The Metric: For these specific fathers, a trip to the cinema is treated as a premium, dedicated "father-daughter experiential event." This intense intentionality spikes their conversion rate to 45%.The Budget Strategy: We allocate a matching 25% of the budget here, but instead of broad awareness, it is hyper-targeted toward premium, high-margin channels, like sportscast programming and premium format theater geofencing.


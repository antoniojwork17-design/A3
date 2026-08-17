

#### Saludo 
Good morning, everyone. My name is [Name], and I’d like to present the project I’ve been working on, called **[Project Name]**.

#### slide 1
First, let’s start with some background. We already had a cycle time calculation; however, it was limited by some time factors. Additionally, there was no historical data available to compare results across different days or weeks. As a result, the analysis was slower, since it had to be done line by line, leading to slower issue detection and decision-making.

#### Slide 2
A benchmark was conducted with Juarez 1 plant, where differences in the cycle time calculation were identified. This analysis made it clear that our current calculation had opportunities for improvement.

#### Slide 3
**Before the benchmark with Juarez 1, our cycle time calculation was limited to a two-hour window, which meant we were losing production records from the full day and week, with no historical data available for comparison.**

**We also identified factors that could inflate the cycle time, such as invalid data. For example, if a part is produced, then production switches to another part and later returns to the original one, the time between those production periods can create an artificially high cycle time. This time should be excluded from the calculation.**

**Additionally, parts produced during planned downtime were included in the calculation, which also increased the cycle time. These factors needed to be filtered out to obtain a more accurate representation of the actual production cycle time.**

#### Slide 4
**With the following solution, we aim to provide teams with more consistent and reliable cycle time calculations that can serve as a reference for identifying issues faster and improving decision-making across production lines.**

#### Slide 5
**What we do is exclude any part that occurs during or overlaps with planned downtime. This prevents the cycle time from being artificially inflated.**

**The same logic is applied when two different part numbers are produced on the same line, ensuring that the time between production runs does not incorrectly affect the cycle time calculation.**

**Once we have clean data, we apply a Z-score to determine how many standard deviations each cycle time is above or below the average. This allows us to include the largest possible number of valid production records while filtering out anomalies that could affect the cycle time calculation.**


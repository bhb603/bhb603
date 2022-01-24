# The Four Keys

Google's DevOps Research and Assessment (DORA) team, which has been publishing annual "State of DevOps" reports since 2014, has distilled the performance of a software development team down to four metrics:

- Deployment Frequency - how often an org releases to production
- Lead Time for Change - how long it takes a commit to get into production
- Change Failure Rate - percentage of deployments causing a failure in production
- Time to Restore Service - How long it takes to recover from a production failure

The first two measure velocity, while the second two measure stability.

An additional fifth metric, Reliability, represents operational performance.
It is the degree to which a team can keep promises about the software they operate (e.g. SLAs or SLOs).

The State of Devops 2021 report identifies four performance profiles: elite, high, medium, and low, as shown in the table below.
High performing teams tend to do better in all four metrics, and accordingly, low performing teams tend to do worse in all metrics.

| Metric                  | Elite   | High       | Medium       | Low       |
| ----------------------- | ------- | ---------- | ------------ | --------- |
| Deploy frequency        | >1/day  | 1/w - 1/mo | 1/mo - 1/6mo | < 1/6mo   |
| Lead time for changes   | < 1h    | 1d - 1w    | 1 - 6mo      | > 6 mo    |
| Time to restore service | < 1h    | < 1d       | 1d - 1w      | > 6 mo    |
| Change failure rate     | 0 - 15% | 16 - 30%   | 16 - 30%     | 16 - 30%  |



**Sources**

- https://cloud.google.com/blog/products/devops-sre/using-the-four-keys-to-measure-your-devops-performance
- https://cloud.google.com/blog/products/devops-sre/the-2019-accelerate-state-of-devops-elite-performance-productivity-and-scaling


---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/14316120?"
user: bwpriest
date: 2024-10-09
repo_name: LLNL/saltatlas
html_url: https://github.com/LLNL/saltatlas/issues/81
repo_url: https://github.com/LLNL/saltatlas
---

<a href='https://github.com/bwpriest' target='_blank'>bwpriest</a> open issue <a href='https://github.com/LLNL/saltatlas/issues/81' target='_blank'>LLNL/saltatlas#81</a>.

<p>metric_hyperplane_partitioner is not compatible with key-value containers</p><small>Currently in `v0.3-dev`, if you pass a key-value store to `saltatlas::dhnsw::partition_data()`, such as a `ygm::container::map`, the `for_all()`s in `saltatlas::metric_hyperplane_partitioner` barf because they expect a bag of pairs. The offending lines occur  [here](https://github.com/LLNL/saltatlas/blob/v0.3-dev/include/saltatlas/partitioner/metric_hyperplane_partitioner.hpp#L55-L60), [here](https://github.com/LLNL/saltatlas/blob/v0.3-dev/include/saltatlas/partitioner/metric_hyperplane_partitioner.hpp#L202-220), [here](https://github.com/LLNL/saltatlas/blob/v0.3-dev/include/saltatlas/partitioner/metric_hyperplane_partitioner.hpp#L499-516), and [here](https://github.com/LLNL/saltatlas/blob/v0.3-dev/include/saltatlas/partitioner/metric_hyperplane_partitioner.hpp#L542-L568)....</small><a href='https://github.com/LLNL/saltatlas/issues/81' target='_blank'>View Comment</a>
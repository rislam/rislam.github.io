+++
title = "Anomaly detection with human feedback"
slug = "anomaly-detection"
date = "2017-01-01"
+++


# Anomaly detections

Anomaly detections are well studied as an Unsupervised Learning problem. And we are trying to answer how we can learn an optimal anomaly detector by asking labels from human. Hence, the name came as Active Anomaly Detection. This work is the most updated and recent work (Das et al., 2019).
References

1. Effectiveness of Tree-based Ensembles for Anomaly Discovery: Insights, Batch and Streaming Active Learning. Das, Shubhomoy, Islam, Md Rakibul, Jayakodi, Nitthilan Kannappan, and Doppa, Janardhan Rao In arXiv preprint arXiv:1901.08930 2019 [Abs]

    > In many real-world AD applications including computer security and fraud prevention, the anomaly detector must be configurable by the human analyst to minimize the effort on false positives. One important way to configure the detector is by providing true labels (nominal or anomaly) for a few instances. Recent work on active anomaly discovery has shown that greedily querying the top-scoring instance and tuning the weights of ensemble detectors based on label feedback allows us to quickly discover true anomalies.

    > This paper makes four main contributions to improve the state-of-the-art in anomaly discovery using tree-based ensembles. First, we provide an important insight that explains the practical successes of unsupervised tree-based ensembles and active learning based on greedy query selection strategy. We also present empirical results on real-world data to support our insights and theoretical analysis to support active learning. Second, we develop a novel batch active learning algorithm to improve the diversity of discovered anomalies based on a formalism called compact description to describe the discovered anomalies. Third, we develop a novel active learning algorithm to handle streaming data setting. We present a data drift detection algorithm that not only detects the drift robustly, but also allows us to take corrective actions to adapt the anomaly detector in a principled manner. Fourth, we present extensive experiments to evaluate our insights and our tree-based active anomaly discovery algorithms in both batch and streaming data settings. Our results show that active learning allows us to discover significantly more anomalies than state-of-the-art unsupervised baselines, our batch active learning algorithm discovers diverse anomalies, and our algorithms under the streaming-data setup are competitive with the batch setup.

<!-- Eurytus Hector, materna ipsumque ut Politen, nec, nate, ignari, vernum cohaesit sequitur. Vel **mitis temploque** vocatus, inque alis, _oculos nomen_ non silvis corpore coniunx ne displicet illa. Crescunt non unus, vidit visa quantum inmiti flumina mortis facto sic: undique a alios vincula sunt iactata abdita! Suspenderat ego fuit tendit: luna, ante urbem Propoetides **parte**. -->

{{< css.inline >}}

<style>
.canon { background: white; width: 100%; height: auto; }
</style>

{{< /css.inline >}}

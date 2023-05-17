# Revising-Mutual-Information-By-Rethinking-Minimal-Sufficient-Representation-in-Contrastive-Leaning
In the discipline of self-supervised representation learning, contrastive learning between various views of the data achieves amazing success, and the learnt representations
are helpful in a variety of downstream tasks such as classification, detection and segementation etc . Contrastive learning roughly achieves the minimal sufficient representation that incorporates the shared information and excludes the non-shared information
between views because all supervisory information for one view originates from the
other view. Given the variety of the downstream activities, it cannot be ensured that all
information pertinent to the task is transmitted between views.As a result, we make the
assumption that non-shared task-relevant information cannot be disregarded and theoretically demonstrate that the minimal sufficient representation in contrastive learning is
insufficient for the downstream tasks, which results in performance loss.From our study,
We propose a solution for this problem .The possibility of the contrastive learning models over-fitting to the shared information between perspectives is revealed, which is a
new issue. As a workaround for this issue, as we are unable to use any downstream task
information during training, we suggest increasing the mutual information between the
representation and input as a regularisation to roughly provide more task-relevant information. Our experiments support the validity of our analysis and the efficiency of our
approach. It considerably raises the efficiency of a number of conventional contrastive
learning models in downstream tasks.

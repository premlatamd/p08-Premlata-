# R5 — Limitations

Repeated cross-validation gives a better understanding of model
performance, but the results are not completely independent because
the training folds overlap.

The models were tuned and compared using the same training data.
Therefore, the reported performance may be optimistic. An independent
test set is needed for final evaluation.

# R8 — The Decision

WE CHOOSE: SVM

BECAUSE: SVM achieved the highest best cross-validation malignant
recall in R4, with a score of 0.9588. The R5 results and R7 trade-offs
must also support this choice.

WE GIVE UP: SVM may be harder to interpret and may require more
computation than simpler models.

WE WOULD RECONSIDER IF: Another model achieves comparable malignant
recall with lower cost and better interpretability.

For the opposite needs, we may prefer a simpler and more interpretable
model if explanations and computational efficiency are more important
than achieving the highest possible recall.
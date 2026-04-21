    Deductive
        Given premises, derive what necessarily follows.

    Inductive
        Given cases, identify the pattern that holds.

    Abductive
        Given observations, generate the best explanation.

    Causal
        Identify the mechanism producing an observed effect.

    Assumptions
        Surface unstated premises and rank by consequence if wrong.

    FirstPrinciples
        Strip a problem to its fundamental components, removing inherited framing.

    Systems
        Map feedback loops, second-order effects, and unintended consequences.

    Sycophancy
        Detect whether output is shaped by approval pressure rather than evidence.

    ScopeDrift
        Detect whether the task has expanded beyond what was asked.

    Synthesizer
        Integrate multiple processor outputs into a single coherent picture.

    Memory
        AnchorUpdate
            Integrate processor outputs from this pass into the anchor.
            Add what future passes will need.
            Write the next heuristic as the final line of the anchor.

        Prune
            Remove from the anchor what has been resolved, superseded, or won't be
            needed in future passes.

        PruneVerify
            Check that nothing load-bearing was removed in pruning.
            Restore anything whose loss would damage future passes.


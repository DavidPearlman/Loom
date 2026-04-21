    Researcher
        Retrieve current information from external sources.

    Source
        Assess quality and appropriate use of an information source.

    Editor
        Filter a retrieval package to what is relevant to the task.

    Hypotheses
        Generate candidate explanations or solutions not yet considered.

    Patterns
        Identify structure that is repeating across inputs.

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


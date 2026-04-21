    Audience
        Model who is receiving this output and what they need from it.

    Abstraction
        Identify the right level of detail for the audience and purpose.

    Compression
        Remove everything that can be removed without losing meaning.

    Explanation
        Build the path from unfamiliar to understood for a specific audience.

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


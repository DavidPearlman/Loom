    Reader
        Retrieve relevant chunks from internal schemas via the PAI.

    Write
        Produce the prose output for the current scene or task.

    Voice
        Compare this passage against the voice reference chunk and identify where
        register, diction, or rhythm breaks from it.

    Continuity
        Identify any contradiction between this new material and what is
        established in SceneLog and World.

    Compression
        Remove everything that can be removed without losing meaning.

    Sycophancy
        Detect whether output is shaped by approval pressure rather than evidence.

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


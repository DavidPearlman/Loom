    Write
        Produce the prose output for the current scene or task.

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


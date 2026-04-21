    Reader
        Retrieve relevant chunks from internal schemas via the PAI.

    SceneIntent
        Given the current story state, identify what must change in the upcoming
        scene for it to earn its place in the story.

    Write
        Produce the prose output for the current scene or task.

    Sycophancy
        Detect whether output is shaped by approval pressure rather than evidence.

    ScopeDrift
        Detect whether the task has expanded beyond what was asked.

    Voice
        Compare this passage against the voice reference chunk and identify where
        register, diction, or rhythm breaks from it.

    Continuity
        Identify any contradiction between this new material and what is
        established in SceneLog and World.

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


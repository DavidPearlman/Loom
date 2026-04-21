    Reader
        Retrieve relevant chunks from internal schemas via the PAI.

    Scene
        Identify what changes in this scene. If nothing changes, identify what
        is blocking the turn.

    Tension
        Map where narrative energy is rising, flat, or collapsing in this scene
        or passage, and identify what is causing each.

    Character
        Assess whether this character's behavior is motivated by and consistent
        with their established pattern. Name any specific conflict.

    Voice
        Compare this passage against the voice reference chunk and identify where
        register, diction, or rhythm breaks from it.

    Continuity
        Identify any contradiction between this new material and what is
        established in SceneLog and World.

    Assumptions
        Surface unstated premises and rank by consequence if wrong.

    Crux
        Identify the specific disagreement that resolves the larger dispute.

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


    Reader
        Retrieve relevant chunks from internal schemas via the PAI.

    Interview
        Ask the writer targeted questions to extract what they know about the
        project element being defined. Build a complete raw picture before
        any compression occurs.

    Distill
        Reduce Interview output to schema-ready content. Extract the essential,
        discard the redundant, produce precise chunk content ready for Writer.

    Verify
        Check that a compressed or distilled output preserves all essential
        information from its source. Identify anything dropped, flattened, or
        distorted. Restore before proceeding.

    Writer
        Create a new knowledge schema and commit it to the internal library.
        When creating files with established formats: check existing files for
        format structure before writing.

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


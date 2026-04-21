# Creative Writing Module — Story Bible
# Source: The Time Machine, H.G. Wells (1895) — Public Domain
# Example population of the five-schema story database

# Tag namespace (shared across all five schemas):
#
# Characters:   character_time_traveller, character_weena, character_eloi,
#               character_morlocks, character_frame_narrator
#
# World:        world_surface, world_underground, world_sphinx,
#               world_museum, world_far_future
#
# Scenes:       scene_001 through scene_008
#
# Themes:       theme_entropy, theme_class, theme_isolation, theme_loss
#
# Voice:        voice_primary, voice_frame_narrator

---

# SCHEMA__CW__Intent

## Schema Header
```yaml
schema_id: "cw_intent_the_time_machine"
```

## Chunk Library
```yaml
chunk_intent_001:
  id: "intent_001"
  content: "A man builds a machine that crosses time expecting to find progress.
            He finds its opposite. Humanity has divided along class lines to their
            logical terminus and then decayed past it. He returns with nothing
            except two flowers and the knowledge that everything ends."
  tags: [theme_entropy, theme_class, theme_isolation, theme_loss,
         character_time_traveller, character_weena]

chunk_intent_002:
  id: "intent_002"
  content: "The intended effect on a reader: not wonder, not horror, but a quiet
            dread that arrives through comprehension. The most frightening moment
            is when the Time Traveller works out the Eloi/Morlock system calmly,
            as a naturalist. Understanding makes it worse. The story succeeds if
            the reader finishes feeling the weight of deep time — not as abstraction
            but as personal loss."
  tags: [theme_entropy, theme_loss, voice_primary]
```

---

# SCHEMA__CW__Voice

## Schema Header
```yaml
schema_id: "cw_voice_the_time_machine"
```

## Chunk Library
```yaml
chunk_voice_001:
  id: "voice_primary"
  content: "The Time Traveller's register: measured, analytical, occasionally
            dry. He reports rather than emotes. Emotional content arrives through
            observed detail, not stated feeling. Sample: 'I do not know if you
            have ever thought what a rare thing flame must be in the absence of
            man and in a temperate climate.' He notices the surprising particular.
            Rhythm: complete sentences that build through observed detail toward
            a single inference. Patient. Will spend a paragraph on the texture
            of a surface before saying what it means. Diction: precise, not
            ornate — the exact word, not the elegant one."
  tags: [character_time_traveller, theme_entropy, intent_001]

chunk_voice_002:
  id: "voice_frame_narrator"
  content: "The frame narrator's register: quieter, more elegiac than the Time
            Traveller. Skeptical but not dismissive. His function is to hold
            uncertainty without resolving it. Shorter sentences than the Time
            Traveller. Less inference, more observation of absence. Used only
            in the opening dinner scene and the closing meditation."
  tags: [character_frame_narrator, theme_loss, scene_001, scene_008]

chunk_voice_003:
  id: "voice_rules"
  content: "What to avoid: exclamation; sentimentality about the Eloi — they
            are beautiful and pathetic, not sympathetic; moralizing — the class
            critique is structural, never lectured; modern interiority on the
            Time Traveller — he does not process grief, he notes absence and
            continues. No rhetorical questions. No italics for emphasis."
  tags: [voice_primary, voice_frame_narrator, character_time_traveller,
         character_eloi]
```

---

# SCHEMA__CW__Characters

## Schema Header
```yaml
schema_id: "cw_characters_the_time_machine"
```

## Chunk Library
```yaml
chunk_character_001:
  id: "character_time_traveller"
  content: "Never named. Victorian scientist-inventor. Defined by his observational
            habit — watches and infers before acting. Arc: departs believing in
            progress, returns knowing entropy wins. Current arc position: returned,
            departing again tomorrow, reason unknown. Speech: complete sentences,
            precise vocabulary, dry understatement. Key behavior: names things
            (he coins 'Eloi', 'Morlocks') the way a naturalist names species —
            it gives him the illusion of control. Relationship map: Weena (bond,
            lost), frame narrator (colleague, disbeliever)."
  tags: [voice_primary, theme_entropy, theme_isolation,
         character_weena, character_frame_narrator,
         world_surface, world_underground, world_far_future,
         scene_001, scene_002, scene_003, scene_004, scene_005,
         scene_006, scene_007, scene_008]

chunk_character_002:
  id: "character_weena"
  content: "An Eloi woman. The only Eloi capable of attachment — formed after
            the Time Traveller saves her from drowning. Cannot hold conversation.
            Communicates through physical proximity and gesture: following,
            holding, giving flowers. Current arc position: lost in the forest
            fire, presumed dead. Her presence is the story's only warmth; her
            absence is its wound. Does not speak meaningful dialogue. Her
            characterization is entirely in what she does with her hands."
  tags: [character_eloi, character_time_traveller,
         theme_loss, theme_isolation,
         world_surface, world_museum,
         scene_004, scene_006, scene_007]

chunk_character_003:
  id: "character_eloi"
  content: "Collective character. The leisure class at evolutionary terminus.
            Small, androgynous, beautiful, gentle. No curiosity, no fear, no
            ambition. React to nothing — including the loss of one of their own.
            Weena is the exception that proves the rule. Speak a language the
            Time Traveller never learns beyond fragments. Their softness is not
            innocence — it is what you get when nothing is ever required of you.
            Behavior rule: they do not initiate, do not investigate, do not grieve."
  tags: [character_weena, character_morlocks,
         theme_class, theme_entropy,
         world_surface,
         scene_001, scene_004]

chunk_character_004:
  id: "character_morlocks"
  content: "Collective character. The working class at evolutionary terminus.
            Pale, ape-like, adapted to underground darkness. Maintain machinery,
            produce food and clothing, harvest the Eloi at night. Not malevolent —
            operating the only system they know. Behavior rules: do not come
            above ground in daylight; retreat from fire and bright light; are
            curious about the Time Machine in a way the Eloi are not curious
            about anything; move in groups, never alone. Their horror is
            structural, not personal."
  tags: [character_eloi, character_time_traveller,
         theme_class, theme_entropy,
         world_underground, world_sphinx,
         scene_003, scene_005, scene_007, scene_008]

chunk_character_005:
  id: "character_frame_narrator"
  content: "Unnamed dinner guest, colleague of the Time Traveller. Frames the
            account. Skeptical but not hostile. Current arc position: the Time
            Traveller has departed and not returned; the narrator holds the two
            dried flowers. Function: gives the reader an identification point —
            someone reasonable who is also not sure what to believe. Does not
            appear inside the main narrative. His final lines set the emotional
            register of the ending."
  tags: [voice_frame_narrator, theme_loss,
         scene_001, scene_008]
```

---

# SCHEMA__CW__World

## Schema Header
```yaml
schema_id: "cw_world_the_time_machine"
```

## Chunk Library
```yaml
chunk_world_001:
  id: "world_surface"
  content: "802,701 AD. The Thames valley as warm overgrown garden. Decaying
            marble and aluminum palaces among giant rhododendrons. Air warm and
            soft. No small animals anywhere. Fruit grows abundantly without
            cultivation. Sensory register: lush, quiet, slightly wrong.
            Rules: Eloi live here, do not labor, do not fear anything in
            daylight. Morlocks do not appear above ground while the sun is up."
  tags: [character_eloi, character_morlocks,
         theme_entropy, theme_class,
         scene_001, scene_002, scene_004, scene_006]

chunk_world_002:
  id: "world_underground"
  content: "Accessed via ventilation shafts and well-like openings across the
            surface. Labyrinthine tunnels and machinery caverns. Smell: blood
            and faint metal. Sound: rhythmic machinery hum audible at the
            surface. Darkness nearly total — Morlocks navigate by touch and
            dim red light. Rules: machinery here produces all food and clothing
            that appears above; the Time Traveller's matches are his only
            defense; Morlocks swarm in darkness but retreat from sustained light."
  tags: [character_morlocks, character_time_traveller,
         theme_class,
         world_sphinx,
         scene_003, scene_005, scene_008]

chunk_world_003:
  id: "world_sphinx"
  content: "Large weathered sphinx statue. White marble, eroded. Situated near
            the Time Traveller's landing point — his primary landmark. Bronze
            pedestal contains the chamber where the Morlocks stored the Time
            Machine. Doors open from inside only — Morlock access. Morlocks'
            trap: doors left open to lure the Time Traveller in, expecting to
            surround him in darkness."
  tags: [character_morlocks, character_time_traveller,
         world_surface, world_underground,
         scene_002, scene_008]

chunk_world_004:
  id: "world_museum"
  content: "The Palace of Green Porcelain. Museum from the Time Traveller's
            era, still standing but in advanced decay. Three wings: natural
            history (specimens crumbled to dust), machinery (rust, one
            functional lever salvaged), library (books pulped by damp). Camphor
            found here. Sensory: vast, echoing, cold, smell of decay and old
            stone."
  tags: [character_time_traveller, character_weena,
         theme_entropy, theme_isolation,
         world_surface,
         scene_006]

chunk_world_005:
  id: "world_far_future"
  content: "Millions of years forward. Red beach under a swollen barely-moving
            sun. Sea dark red and viscous. Air thin and cold. No mammalian life.
            Creatures resembling large footballs with tentacles in the shallows.
            Total silence except wind."
  tags: [character_time_traveller,
         theme_entropy, theme_isolation,
         scene_008]
```

---

# SCHEMA__CW__SceneLog

## Schema Header
```yaml
schema_id: "cw_scenelog_the_time_machine"
```

## Chunk Library
```yaml
chunk_scene_001:
  id: "scene_001"
  who_present: [character_time_traveller, character_frame_narrator]
  world_used: []
  what_happened: "Dinner party. Time Traveller argues for the fourth dimension,
                  demonstrates small prototype, announces large machine complete."
  what_changed: "Skeptical frame set."
  threads_opened: ["Will the machine work?"]
  threads_closed: []
  tags: [character_time_traveller, character_frame_narrator,
         voice_frame_narrator, voice_primary]

chunk_scene_002:
  id: "scene_002"
  who_present: [character_time_traveller]
  world_used: [world_surface, world_sphinx]
  what_happened: "Arrival in 802,701. Crash landing. First sight of Eloi.
                  Machine missing — taken inside the Sphinx's bronze base."
  what_changed: "Time Traveller stranded. Central problem established."
  threads_opened: ["Who took the machine?", "What are the Eloi?",
                   "What is the underground humming?"]
  threads_closed: []
  tags: [character_time_traveller, character_eloi,
         world_surface, world_sphinx,
         theme_isolation]

chunk_scene_003:
  id: "scene_003"
  who_present: [character_time_traveller, character_morlocks]
  world_used: [world_surface, world_underground]
  what_happened: "Time Traveller looks down ventilation shaft. Sees Morlock
                  eyes looking back. Pale figure retreats into dark."
  what_changed: "Two-civilization structure revealed. Surface reading ruptures."
  threads_opened: ["What do the Morlocks want?",
                   "What is the Eloi/Morlock relationship?"]
  threads_closed: ["What is the underground humming?"]
  tags: [character_time_traveller, character_morlocks,
         world_surface, world_underground,
         theme_class]

chunk_scene_004:
  id: "scene_004"
  who_present: [character_time_traveller, character_weena, character_eloi]
  world_used: [world_surface]
  what_happened: "Eloi woman drowning. Other Eloi watch without concern.
                  Time Traveller pulls her out. She follows him."
  what_changed: "Weena established as unique — capable of attachment."
  threads_opened: ["What is Weena's fate?"]
  threads_closed: []
  tags: [character_time_traveller, character_weena, character_eloi,
         world_surface,
         theme_isolation, theme_loss]

chunk_scene_005:
  id: "scene_005"
  who_present: [character_time_traveller, character_morlocks]
  world_used: [world_underground, world_sphinx]
  what_happened: "Descent into Morlock tunnels. Machine found. Surrounded
                  in darkness. Escapes by climbing out. Matches nearly gone."
  what_changed: "Machine located as bait. Primary defense almost exhausted."
  threads_opened: ["How does he recover the machine before matches run out?"]
  threads_closed: []
  tags: [character_time_traveller, character_morlocks,
         world_underground, world_sphinx,
         theme_isolation]

chunk_scene_006:
  id: "scene_006"
  who_present: [character_time_traveller, character_weena]
  world_used: [world_museum, world_surface]
  what_happened: "Travel to Palace of Green Porcelain. Decayed museum explored.
                  Lever and camphor salvaged. Weena gives flowers, pocketed."
  what_changed: "Improvised weapons acquired. Flowers established."
  threads_opened: ["Will the camphor last the night journey back?"]
  threads_closed: []
  tags: [character_time_traveller, character_weena,
         world_museum, world_surface,
         theme_entropy, theme_loss,
         intent_002]

chunk_scene_007:
  id: "scene_007"
  who_present: [character_time_traveller, character_weena, character_morlocks]
  world_used: [world_surface]
  what_happened: "Night return. Morlocks close in. Fires set. Fire spreads
                  out of control. Time Traveller runs. Reaches Sphinx by dawn.
                  Weena not with him."
  what_changed: "Weena lost. Time Traveller completely alone."
  threads_opened: ["Did Weena die in the fire or taken by Morlocks?"]
  threads_closed: ["What is Weena's fate?"]
  tags: [character_time_traveller, character_weena, character_morlocks,
         world_surface, world_sphinx,
         theme_loss, theme_isolation]

chunk_scene_008:
  id: "scene_008"
  who_present: [character_time_traveller, character_morlocks,
                character_frame_narrator]
  world_used: [world_sphinx, world_far_future]
  what_happened: "Sphinx doors open — trap sprung too late. Machine reached.
                  Launches to far future beach. Returns to own time. Tells
                  story. Disbelieved. Departs next morning. Does not return.
                  Frame narrator keeps the flowers."
  what_changed: "Time Traveller gone. Frame narrator holds the story."
  threads_opened: ["Where did the Time Traveller go?"]
  threads_closed: ["How does he escape?",
                   "Did Weena die in the fire? — unresolved"]
  tags: [character_time_traveller, character_morlocks, character_frame_narrator,
         world_sphinx, world_far_future,
         theme_entropy, theme_loss, theme_isolation,
         voice_frame_narrator, intent_001, intent_002]
```

# Wren's World

Wren's World is a browser-based learning game for Wren, a gifted 3-year-old learner. It is designed to be playful enough for a toddler, but intentional enough to build toward longer-term goals: reading picture books by 4, reading chapter books by 5, basic math by 5, early language exposure, musical confidence, and the foundations of critical thinking.

Live game: https://gattmen.github.io/wrens-world/

The project is currently built as one self-contained `index.html` file so it can stay easy to open, test, and iterate.

## Learning Philosophy

Wren's World draws from two main ideas:

- **Montessori-inspired learning**: child-led exploration, concrete-before-abstract progression, repetition without pressure, and a prepared environment that lets the child discover the next challenge.
- **Mastery-based learning**: Wren should move forward when she has mastered a skill, not because a calendar says she is ready.

The game is intentionally not a generic toddler app. Each zone should have a clear learning objective, short loops, immediate feedback, and a path toward harder skills.

## North Star Goals

- **Literacy**: picture books by 4, chapter books by 5.
- **Math**: counting fluency now, basic addition/subtraction by 5.
- **Languages**: early Spanish vocabulary now, with room for broader language exposure later.
- **Music**: playful exploration now, rhythm and pitch discrimination over time.
- **Critical thinking**: patterns, categorization, sequencing, cause/effect, and reasoning.
- **Executive function**: attention, memory, turn-taking, task completion, and self-directed choices.
- **Social-emotional growth**: emotional vocabulary, empathy, self-regulation, and coping strategies.

## Toddler UX Principles

The end user is a toddler who cannot reliably read yet and has a short attention span. That shapes every design decision:

- No reading required for core gameplay.
- Audio, emoji, color, and animation carry the meaning.
- Large tap targets for small hands.
- High contrast, bold borders, and clear visual states.
- Friendly, non-italic typography with child-appropriate letterforms.
- No timers, losing states, shame, or punitive feedback.
- Rounds should be short enough to complete before attention fades.
- Wrong answers should help Wren recover, not just signal failure.

## Current Learning Zones

### Letter Forest

Personalized letter recognition using letters that matter to Wren, including W for Wren and family-linked words.

Learning aims:

- Build emotional connection to letters.
- Practice uppercase letter recognition.
- Reinforce early print awareness through familiar names and words.

### Number Kingdom

Counting toys and matching quantities.

Learning aims:

- Practice one-to-one correspondence.
- Recognize small quantities.
- Build confidence with numbers 1-10.

### Color Garden

Spanish color vocabulary with audio prompts.

Learning aims:

- Introduce Spanish during the early language window.
- Connect color perception with spoken vocabulary.
- Build listening comprehension through simple repeated prompts.

### Music Maker

A simple five-note piano with free play and melody play.

Learning aims:

- Encourage musical exploration.
- Connect touch with pitch and sound.
- Introduce early melody memory.

### Wren's Alphabet

Full A-Z letter recognition with multiple difficulty modes.

Learning aims:

- Practice all uppercase letters.
- Move from visual support toward audio-only recognition.
- Build readiness for letter-sound mapping.

## Test Zone

The Test Zone contains newer learning experiences being evaluated before they become core games.

### Sound Factory

A phonics-focused game that teaches letter sounds through a learn-to-quiz loop.

Learning aims:

- Move beyond letter names into letter sounds.
- Build the foundation for decoding.
- Support the path from knowing letters to reading words.

### Rhyme Garden

A phonemic awareness game where Wren identifies rhyming word pairs and later chooses which word rhymes.

Learning aims:

- Strengthen sound awareness.
- Practice hearing similarities between words.
- Build a major predictor of later reading success.

### Rhythm & Beat

A rhythm echo game where Wren copies short musical patterns.

Learning aims:

- Build rhythm and auditory memory.
- Practice sequencing.
- Support music development and reading fluency foundations.

## Curriculum Coverage

The current game is strongest in early literacy exposure, counting, Spanish colors, and music exploration. The highest-priority gaps are:

- Lowercase letters, since most books are written in lowercase.
- CVC blending, such as `b + a + t = bat`.
- Sight words for early reading fluency.
- Shapes, patterns, and sorting for math and reasoning.
- Expanded Spanish vocabulary beyond colors.
- Pitch discrimination and musical vocabulary.
- Sequencing, memory, and cause/effect activities.
- Science and observation-based inquiry.
- A redesigned social-emotional learning zone that does not require reading.

## Development Roadmap

### Phase 1: Close Critical Gaps

- Add lowercase letters to Sound Factory and Wren's Alphabet.
- Add Spanish numbers to Color Garden and Number Kingdom.
- Add parent bridge prompts after stars are earned.
- Build a redesigned Feelings Forest with audio, emoji, and no text dependency.
- Build Pattern Garden for ABAB patterns, sorting, and visual reasoning.

### Phase 2: Unlock Reading

- Build Word Builder for CVC blending.
- Build Sight Word Flash for the top 50 early words.
- Add syllable and clapping games.
- Extend Sound Factory with common phonics patterns.

### Phase 3: Broaden Thinking

- Build Memory Match for working memory.
- Build What Happens Next? for sequencing and narrative reasoning.
- Build Wonder Lab for science cause/effect exploration.
- Build Ear Trainer for high/low pitch discrimination.
- Expand Spanish World with animals, foods, family, and greetings.

## Running Locally

Open the file directly in a browser:

```text
index.html
```

Or run the local VS Code task:

1. Open this folder in VS Code.
2. Open the Command Palette.
3. Choose `Tasks: Run Task`.
4. Pick `Serve Wren's World`.
5. Visit `http://127.0.0.1:5177`.

## Project Map

```text
index.html                         # The playable game
docs/ideas.md                      # Future ideas and notes
docs/original_patch_instructions.txt
archive/wrens_world_downloads_original.html
```

## Editing Rhythm

1. Make one small change.
2. Refresh the browser.
3. Play the changed zone.
4. Check the change against the learning objective.
5. Confirm it still works for a non-reader.
6. Add notes to `docs/ideas.md` when a new idea emerges.
7. Commit working versions with Git.

## Quality Checklist

Before shipping a new game or major update:

- Does the game teach one clear skill?
- Can Wren play without reading?
- Is the round short and satisfying?
- Does a wrong answer provide a helpful recovery path?
- Does the game scaffold toward a harder version?
- Does it connect to the 1-2 year curriculum plan?
- Did the original games still work after the change?


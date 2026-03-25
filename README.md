Automata Simulator with Animation
🌟 Features
🤖 Automata Types
DFA (Deterministic Finite Automaton) - Single deterministic path per input symbol

NFA (Nondeterministic Finite Automaton) - Multiple possible transitions

ε-NFA - NFA with epsilon (empty string) transitions

Regular Expressions - Build automata from regex patterns

PDA (Pushdown Automaton) - Stack-based automata for context-free languages

🎮 Interactive Controls
Step-by-step animation - Watch each transition as it happens

Run full simulation - Automatic processing of entire input string

Reset simulation - Clear current state and start over

Download diagram - Export automaton visualization as PNG

✏️ State Management
Add, delete, and modify states

Mark states as initial or final

Drag and drop states anywhere on canvas

Visual feedback for current states and transitions

🔄 Transition Management
Support for multiple symbols per transition (0, 1, ε)

PDA transitions with stack operations (push/pop)

Self-loop transitions

Visual highlighting of active transitions during simulation

🎨 Visual Features
Smooth animations with color-coded states:

🔵 Blue: Initial state

🟢 Green: Final state

🟣 Purple: Both initial and final

🔴 Red: Current active state

Pulsing highlight effects for active states

Dashed line animation for active transitions

Real-time stack visualization for PDA

 Usage Guide
Getting Started
Select Automata Type - Choose from DFA, NFA, ε-NFA, Regular Expression, or PDA

Add States - Click "Add State" to create new states

Set Initial/Final States - Use the buttons in the states list to mark state types

Add Transitions - Select symbols and connect states

Enter Input String - Type a string to test (only 0 and 1 for finite automata)

Run Simulation - Click "Run Animation" to watch the automaton process your input

For PDA (Pushdown Automaton)
Select "Pushdown Automaton (PDA)" from the dropdown

Configure stack alphabet and initial stack symbol

Add PDA transitions with:

Input - The symbol to read (or ε)

Pop - The symbol to pop from stack (or ε)

Push - The symbols to push onto stack (or ε)
Enter input string (allowed: 0, 1, a, b)

Run simulation - watch both state and stack changes

Regular Expression Support
The simulator supports building automata from common regex patterns:

Pattern	Language Description
(0|1)*   	All binary strings
(0|1)*01(0|1)*	Strings containing '01'
0*1*	Zero or more 0s followed by zero or more 1s
(00|11)*	Even length strings with alternating pairs

🔧 Technical Details
Built With
HTML5 - Canvas API for rendering

CSS3 - Modern styling with gradients and animations

Vanilla JavaScript - No external dependencies

Key Algorithms
ε-closure computation - For ε-NFA simulation

Thompson's construction - Regex to NFA conversion (simplified)

PDA stack operations - LIFO stack management

Transition traversal - Support for nondeterministic paths

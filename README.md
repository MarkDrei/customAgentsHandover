# Custom Copilots which hand over work as sub-tasks

Simple experiment that tests how two copilot agents work together, when the 'agent' tool is available to the orchestrating agent.

## How to use
Import in VS code and use the boss agent. It should receive a word and delegate this to the 'echo agent', which should convert the word to upper case.

## My Expectation

If I prompt the 'boss' with "The word is foo", then the boss should go to the echo-agent. This then converts the word to "FOO!" and the boss gives me this as a response.

## What actually happens

The echo-agent does not receive its prompt from the echo-agent.agent.md file and does not know how to convert the word.

Note: If the echo-agent is used directly, it performs the conversion without any issues.

# Nuggets — Explanation, Characteristics, Generation
Support for using the nugget style of communication
 * [Explanation](README.md#nugget--explanation)
 * [Characteristics](README.md#nugget--characteristics)
 * [Generation](README.md#generating-a-nugget)
 * [Nugget Development Example](README.md#nugget-development-example)
 * [Etymology](README.md#why-nugget)

## Nugget — Explanation
The "nugget" is a particularly structured form of communication.

The term nugget, in this context, means a single, non-compound, grammatically-correct sentence that effectively and efficiently communicates what you have determined to be most important for a specified audience.

A nugget is always written in the context of an intended audience. Clearly identifying that audience's relevant characteristics is essential. With respect to the intended audience, a nugget represents the distillation of the single most important element from a potentially large collection of useful information.

Nuggets are always expressed in your own words; that is, they must not be direct quotations of others.

## Nugget — Characteristics
### Well-Constructed
A well-considered and well-written nugget has the following characteristics:

    ✔ Single concept  
    ✔ Self-contained (stands on its own)  
    ✔ Succinct (brief; single sentence; simple sentence structure)  
    ✔ High value to intended audience  
    ✔ Grammatically correct


### Poorly-Crafted
Symptoms of a poorly-crafted nugget include:

    ✘ Divisible into multiple separate concepts  
    ✘ Uses compound subject, predicate, or sentence structure  
    ✘ Does not stand on its own; requires additional description or explanation  
    ✘ Lengthy or complex  
    ✘ Already well-appreciated by audience  
    ✘ Marginal significance to audience  
    ✘ Direct quotation


## Generating a Nugget
Here is a step-by-step process for generating a nugget.

1. Write down key characteristics of a typical member of the intended audience for easy reference.
2. Write an extended prose form of important information as source for the nugget.
3. Iterate over the following two activities until a satisfactory result is achieved:  
    3a. Identify and remove some non-essential concept or words from the text; refine the result for readability.  
    3b. Consider how well the result meets the desired characteristics of a well-written nugget for the intended audience.

*Multiple iterations are usually required.*

### Observations
- Crafting a nugget _starts with_ something to be communicated, _"the message"_, _and_ a defined recipient, _"the audience"_.

- The process of developing a nugget usually exposes attributes of the intended message that are inconsistent with the nugget form.

- Common observations made during nugget development:
  - original message contained multiple ideas instead of just one
  - nugget candiate is a mismatch with audience pre-knowledge
  - nugget candidate has excessive length
  - the nugget candidate fails to stand on-its-own

___
## Nugget Development Example

Here's an example of my going through a nugget-development process.

I began by writing down the objective of my communication.

>"My audience are upper-division students who have satisfied lower-division computer science degree requirements and are interested in developing more-usable software.  I want to convey the basic idea that messages presented when software detects an error need to do more than just announce that an error has occurred. They should be even more useful to the recipient of the message.  In particular, and especially when dealing with end-users, the messages should guide the recipient users about what they can or should do next, to keep proceeding forward, to recover, to return to a safe state, or to bail out with the least amount of collateral damage."

Using that text as a starting point, I started deleting words that weren't essential to the final nugget, keeping in mind the characteristics of the intended audience.

>"~~My audience are upper-division students who have satisfied lower-division computer science degree requirements and are interested in developing more-usable software.  I want to convey the basic idea that~~ messages presented when software detects an error need to do more than just announce that an error has occurred. They should be ~~even~~ more useful to the recipient of the message.  ~~In particular, and~~ especially when dealing with end-users, the messages should guide the recipient users about what they can or should do next, to keep proceeding forward, to recover, to return to a safe state, or to bail out with the least amount of collateral damage."

Cleaned up...

>"Messages presented when software detects an error need to do more than just announce that an error has occurred. They should be more useful to the recipient of the message. Especially when dealing with end-users, the messages should guide the recipient users about what they can or should do next, to keep proceeding forward, to recover, to return to a safe state, or to bail out with the least amount of collateral damage."

I then looked to reduce the number of words by finding shorter phrases.

"messages presented when software detects an error" and "the messages" became "error messages".

"the recipient of the message" and "recipient users" became "the user".

>"*Error messages* need to do more than announce that an error has occurred. They should be more useful to users.  Especially when dealing with end-users, *error messages* should guide *the users* about what they can or should do next, to keep proceeding forward, to recover, to return to a safe state, or to bail out with the least amount of collateral damage."

There are too many ideas contained in this passage to send a clear message to the reader; that is, it does not express a single idea.

I needed to identify some of the constituent messages and decide what was most important.

Here are some of the teased-out messages:

- Error messages need to do more than announce that an error has occurred.
- Error messages should be useful to users.
- Error messages are especially important when dealing with end-users.
- Error messages should guide end-users about what they can or should do next.
- Error messages should guide users about what they can or should do next.
- Error messages should guide users about what they can do to keep proceeding forward.
- Error messages should guide users about what they can do to recover.
- Error messages should guide users about what they can do to return to a safe state.
- Error messages should guide users about what they can do to return to bail out with the least amount of collateral damage.

As I thought about the intended audience, I decided that they already knew what "error messages" were, so I didn't need to include that they "announce that an error has occurred."  The statement that "error messages should be useful to users" also didn't seem to add much value to what the audience was likely to already believe.

I also decided that my desired emphasis was to be about **improving** error messages in general, not only those directed at end-users in particular.

The term "users" was also preferable to "end-users" as it is more encompassing and wouldn't necessitate explaining a potentially new term ("end-user").

Here are the remaining messages after prioritizing and pruning based on what I thought was most valuable to the intended audience:

- Error messages should guide users about what they can or should do next.
- Error messages should guide users about what they can or should do to recover.
- Error messages should guide users about what they can or should do to keep proceeding forward.
- Error messages should guide users about what they can or should do to return to a safe state.
- Error messages should guide users about what they can or should do to return to bail out with the least amount of collateral damage.

My identified emphasis on error message *improvement* suggested possible rewrites to the opening phrase.

• One was to change the phrase "error messages should" to "error messages should also".

• Another was to change the phrase "error messages should" to "error messages should be improved to".

After much shuffling around of words, over and over again without reaching a resolution, I decided to retry narrowing down the message.  I put the top two prioritized ideas together as a new starting point.

>"Error messages should also guide users about what they can or should do next to recover."

The word "next" now seemed superfluous.

>"Error messages should also guide users about what they can or should do to recover."

The newly crafted message itself was still obviously compound, using the disjunction "or".

>"Error messages should also guide users about what they can do to recover."  
>"Error messages should also guide users about what they should do to recover."

I deemed the more important message of the two to be "can do" rather than "should do".

>"Error messages should also guide users about what they can do to recover."

Reading this aloud, and hearing it read by a text-to-speech utility, the "error messages should also" seemed both too long and didn't match the tone that I intended.  I realized what I wanted most was to communicate one key characteristic that improves value over typical error messages.  Here's an abbreviated sequence of rewrites.

1. "Error messages that also guide users about what they can do to recover are better than those that do not."
1. "Better error messages are those that also guide users about what they can do to recover."
1. "Better error messages ~~are those that~~ also guide users about what they can do to recover."
1. "Better error messages ~~also~~ guide users about what they can do to recover."
1. "<ins>Good</ins> error messages guide users about what they can do to recover."
1. "Good error messages _suggest what users_ can do to recover."

At this point, I was OK with having created a meaningful and useful message, appropriate to the audience.

However, "what users can do to recover" still didn't feel quite right.  It seemed both too wordy and too specific.

The "too wordy" concern lead to replacing "what users can do" with "how".

>**"Good error messages suggest how to recover."**

The "too specific" concern suggested that I had never actually named the collection of outcomes but only identified examples ("proceed forward", "recover", "get to safe state", "bail out"). As a result, when I teased apart the original into its components and then adopted the phrase "how to recover", I'd lost the collective nature of what I'd wanted to express.

Sadly, I couldn't quickly identify a rewrite to address this weakness.

Rationalizing, this sentence seemed close enough that I could be OK stopping at this sentence as the nugget; but it felt like giving up too soon.

I still wanted to find some word(s) that would better encompass the collection of outcomes that were in the initial set ("proceed forward", "recover", "get to safe state", "bail out") that had been pared down to just "recover".

More brainstorming, consulting dictionaries & thesauruses, taking walks, eating snacks, ignoring the problem, ... _time passes_ ..., perhaps the concept of "remedy"?

The following is the outcome that satisfied the essential characteristics of a nugget: communicating what I thought was most valuable to the specified audience in a way that was efficient and would stand on its own.

>⭐️ **_Good error messages suggest remedies._**

Using the characteristics as checklists to evaluate this *nugget:*
  
✔ Single concept  
✔ Self-contained (stands on its own)  
✔ Succinct (brief; single sentence; simple sentence structure)  
✔ High value to intended audience  
✔ Grammatically correct  
  
✔ Not divisible into multiple separate concepts  
✔ Does not use compound subject, predicate, or sentence structure  
✔ Does not require additional description or explanation  
✔ Is not lengthy or complex  
✔ Is not already well-appreciated by the audience  
✔ Is not of marginal significance to audience  
✔ Does not use a direct quotation  

___
## Why "Nugget"
This use of the word "nugget" derives from its general usage as identifying something small and valuable and the phrase "nugget of wisdom" meaning a concise statement of great value or significance.

___
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Nuggets - Explanation, Characteristics, Generation</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Dr. Jody Paul</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

Document Source Repository: [https://github.com/jody/Nuggets](https://github.com/jody/Nuggets)  
Document Web Hosting: [https://jody.github.io/Nuggets/](https://jody.github.io/Nuggets/)

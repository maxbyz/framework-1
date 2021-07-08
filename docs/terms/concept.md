---
id: concept
title: "Concept"
scopeid: essifLabTerminology
type: concept
typeid: concept
stage: draft
hoverText: "Concept: the ideas/thoughts behind a classification of Entities (what makes Entities in that class 'the same')."
glossaryText: "the ideas/thoughts behind a classification of %%entities^entity%% (what makes %%entities^entity%% in that class 'the same')."
date: 20210601
---

## Definition
A Concept tries to capture the idea behind a classification of entities[^1], allowing us to reason about everything in the class as if it were one thing. For example, the ideas ([mental representations](https://en.wikipedia.org/wiki/Mental_representation)) you have when processing the sentences "I can drink beer from a beer glass' and 'I can drink beer from a coffee mug' shows that the concepts that are behind 'beer glass' and 'coffee mug' differ. Note that in order to communicate about this idea, we also need a word or phrase (i.e.: a term that we can use to refer to (instances of) this idea).

The [terminology pattern](pattern-terminology) provides an overview of how this concept fits in with related concepts.

A practical method for establishing and maintaining terminology that is unambiguous and relevant for a given scope or purpose, and resolving related issues can be found [here](https://www.researchgate.net/publication/352560909_On_Terminology_and_the_Resolution_of_Related_Issues).

## Purpose
Working together is easier when you and your peers share the same ideas. We need a way to test and ensure, that you and your peers _actually_ have the same understanding, for the purpose of making cooperation easier. Doing so is expected to not only reduce the number of terminological discussions, but also improve the efficiency and effectiveness of the remaining discussions.

## Criteria
A (description/specification of a) Concept MUST be [intensionally defined](https://en.wikipedia.org/wiki/Extensional_and_intensional_definitions), i.e. associated with a criterion that can be used to determine whether or not someone or something qualifies as (an instance of) that Concept, and that has the property that it has been shown that the vast majority of contributors and other users apply it in the same manner in different situations (i.e. they arrive at the same conclusion as to whether or not someone or something qualifies under that criterion in any given situation).

## Related Concepts
* [Term](term) is a label that is used in some context to refer to a [Concept](concept)[^2], the set of entities that satisfy the concept's criteria, or an arbitrary element of that set. Different contexts may use different terms to refer to a single concept. In a single context, a single term should be used to refer to an individual concept.
* [Scope](scope) is related in several ways. First, there is (precisely, or at most one) Scope that governs the definition/specification of the Concept. Second, there may be (any number of) Scopes that use the Concept, i.e. within which Terms are defined that refer to the Concept
* [Mental(or Conceptual) Model](pattern) is a collection of concepts, relations between such concepts, and constraint rules that (elements of) such concepts and relations must satisfy. Such [models](https://en.wikipedia.org/wiki/Conceptual_model) are used to help people know, understand, or simulate a subject the model represents.

## Notes

There is an important [distinction between concepts and the (multitude of) terms](https://simple.wikipedia.org/wiki/Concept) (names, labels) that we need to be able to talk and reason (argue) about them. Please consider that

* different terms are used in different contexts for the same concept
* in different contexts, a single term may refer to different concepts
* to resolve terminological disputes, which usually are about the 'correct' meaning of a term, try to establish the criteria that the different participants use for the concept behind the term. That helps participants understand each others (different) positions, and provides a better basis for resolving the conflict.

---
## Footnotes

[^1]: WikiPedia has a concise [explanation of concepts](https://en.wikipedia.org/wiki/Concept). We use the term 'concept' as a [mental representation](https://en.wikipedia.org/wiki/Mental_representation).

[^2]: For the difference between 'Concept' and 'Term', see https://simple.wikipedia.org/wiki/Concept.

## Tags
#ctwg #essiflab #essiflab-framework
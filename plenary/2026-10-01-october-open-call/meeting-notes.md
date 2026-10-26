# DDS Plenary Open Call

**Date:** October 1, 2026

**Scheduled time:** 14:00 to 15:00 UTC

**Event:** [W3C meeting occurrence](https://www.w3.org/events/meetings/5a9efa11-888f-4941-80e8-5b420d4bf5ca/20261001T140000/)

**Recording:** [YouTube](https://youtu.be/OATtqg0ui2Y)

These notes were prepared from the Gemini notes and computer-generated transcript together with the Google Meet side chat. They have not been checked against the recording. The linked transcript is machine-generated and may contain errors.

## Participants Identified in the Records

- Alessandro Oppo
- Akinori Oyama
- Bumblefudge von CASA
- Elianna DeSota, also referred to as Lee
- Nicolas Gimenez
- Simone Vagnoni, facilitating
- Sneha Vijayan
- Stuart Lynn

This is not a complete attendance register. Names are drawn from speaking turns and chat messages.

## Summary

Elianna DeSota presented Metagov's interoperable deliberative tools research, including shared data and ontologies, digital identity, process documentation, AI and facilitation, participation ethics, and democratic culture. Akinori Oyama raised concerns about transparency and evaluation in AI-assisted public consultation.

Building on September's proposal for a lightweight collection of tools and processes, the group discussed how to make that collection useful and accessible. The resulting direction was to start with concrete, implementation-neutral user stories. Those stories should guide the scope of future work, the grouping of related capabilities, and the identification of existing tools or shared infrastructure.

Bumblefudge von CASA offered to share a GitHub issue-template draft with the chairs. Nicolas Gimenez offered to develop the draft and seed an initial set of stories, then invite broader contributions.

## Agreed Direction

- **Start from user needs.** Describe what people need to accomplish through deliberation without assuming a particular protocol, tool, or technical architecture.
- **Use a lightweight submission template.** Collect user stories and use cases through GitHub prompts that make it possible to start with a rough contribution and refine it collaboratively.
- **Seed the process with examples.** An initial handful of stories should help others understand the requested level of detail and contribute their own needs.
- **Let stories guide organization.** Use the emerging stories to identify shared capabilities and manageable areas of parallel work. Earlier track and tool-inventory proposals were discussed, but no final taxonomy or technical standard was adopted.
- **Connect existing work to those needs.** Prior art and process inventories remain useful resources; collecting them is not a substitute for identifying the problems DDS should address.

## Discussion

### Metagov's Interoperable Deliberative Tools Work

Elianna described a research area organized around standards and values. Work on the standards side includes a shared data schema and ontology for deliberative tools, digital identity requirements, reference architectures and run sheets, and AI-assisted facilitation.

The digital identity discussion emphasized requirements from communities facing risks, including the need to speak safely and resist manipulation by bots. Reference-architecture diagrams were presented as a way to document participation, information flows, processing steps, and points of power across deliberative processes.

The AI and facilitation work brings facilitators together with implementation partners to identify useful applications of AI and develop evaluations. Its stated aim is to strengthen participants' deliberative skills rather than replace human interaction or centralize power.

Values-related work includes democratic education, participation ethics, consent and data ownership, local governance of AI, institution design, and opportunities to explore deliberative practice. Nicolas asked about the relationship between the diagrams and the ontology. Elianna clarified that they are not directly linked and offered to check for updated process documentation.

### Public Consultation, Deliberation, and Evaluation

Akinori described an analysis of AI-chatbot-assisted input to a Japanese political party's policy platform. He raised questions about whether public input influences policy, whether feedback is sufficiently transparent, and how such processes can be independently evaluated.

Simone distinguished consultation from deliberation by noting the importance of discussion among participants, while also suggesting that different dialogue types could be represented in a broader conceptual framework. Participants connected evaluation questions to Metagov's AI and facilitation work.

### From a Resource Collection to Concrete Goals

Simone introduced a preliminary spreadsheet of deliberation tools, processes, and research resources. Nicolas emphasized the need to involve facilitators and connect technical choices to the deliberative processes they support. Stuart cautioned that a large undifferentiated collection could be difficult to contribute to or use without clear motivating needs.

Participants discussed using existing resources such as Participedia and process-mapping efforts, rather than recreating them. Organizing contributions by the previously proposed DDS tracks was one option, but the conversation moved toward user stories as an earlier organizing step.

### User Stories and Implementation-Neutral Standardization

Bumblefudge proposed first identifying user stories and capabilities that the group considers in scope, then grouping related stories and mapping existing solutions to them. User stories should describe the value or outcome for an end user; they should not silently prescribe an implementation.

Stuart offered an example involving opinion groups, small-group discussions, transcription, and synthesis across several tools. The discussion highlighted how easy it is for a proposed story to become a technology-specific use case. Iteration between the two can help clarify actual needs.

Grouping stories could also help volunteers work in parallel on bounded goals. Participants discussed the need to keep that work realistic for the time available to chairs and contributors.

### Contributions, Templates, and Outreach

Bumblefudge described a workflow in which contributors propose stories or use cases through prompts, chairs help refine straightforward entries, and uncertain scope questions are brought back to the group. GitHub's accessibility to non-technical contributors was raised as a concern; templates were discussed as one way to reduce the barrier.

Nicolas proposed coordinating an initial template draft with Bumblefudge and the other chairs before inviting public feedback. Akinori asked how potential users and evaluation needs would be identified. Nicolas pointed to existing platforms and their communities as sources of interoperability needs and welcomed contributions from Japanese communities and non-technical participants.

## Next Steps

- **Bumblefudge von CASA:** share a proposed issue-template structure with the chairs.
- **Nicolas Gimenez and the chairs:** refine the template with Bumblefudge, then circulate it for community feedback and contributions.
- **Nicolas Gimenez:** prepare an initial set of user stories to seed the process. The discussion suggested approximately five examples, not a fixed limit on scope.
- **Community participants:** add implementation-neutral needs and help refine the initial stories. Stuart offered to contribute examples.
- **Outreach:** invite potential users and Japanese community perspectives once the template and initial examples are available. Akinori suggested approaching potential users directly.
- **Elianna DeSota:** check with Liz Barry for updated process diagrams and documentation, and identify Metagov materials that can be shared with DDS.

These are plans recorded at the meeting, not a claim that the work has since been completed. No new deadline was agreed.

## Resources Shared

- [Metagov interoperability work map](https://kumu.io/LeeDeSota/metagov-scopes#interop-scopes/standards)
- [Data mesh governance repository](https://github.com/datamesh-governance/datamesh-governance.com)
- [Metagov AI & Facilitation](https://metagov.org/projects/ai-facilitation)
- [Akinori Oyama's public-input analysis](https://github.com/akinorioyama/voices-heard/blob/main/docs/pr_reflection_eval_methods_en.md)
- [W3C Social Web user stories](https://www.w3.org/wiki/Socialwg/Social_API/User_stories#Moving_of_identities)
- [European Parliament study shared by Simone](https://www.europarl.europa.eu/RegData/etudes/STUD/2026/774753/EPRS_STU(2026)774753_EN.pdf)
- [Metagov community introduction](https://metagov.org/join/community)
- [DDS repository](https://github.com/dds-wg/dds/)
- [August plenary presentation](../2026-08-06-august-open-call.pdf)
- [September meeting notes](../2026-09-03-september-open-call/meeting-notes.md)

## Related Records

- [Computer-generated transcript](./transcript.txt)
- [Redacted side chat](./chat-transcript.txt)

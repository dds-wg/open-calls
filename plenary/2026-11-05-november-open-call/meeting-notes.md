# DDS Plenary Open Call

**Date:** November 5, 2026

**Scheduled time:** 14:00 to 15:00 UTC

**Event:** [W3C meeting occurrence](https://www.w3.org/events/meetings/5a9efa11-888f-4941-80e8-5b420d4bf5ca/20261105T140000/)

**Recording:** [W3C DDS Community Group: November Plenary Open Call | Use Cases & System Design](https://youtu.be/bW_8SOyOrPw)

**Status:** Draft for chair review. This AI-assisted summary was prepared from the Gemini notes, computer-generated transcript, and Google Meet side chat. It has not been checked against the published recording.

## Participants Identified in the Records

- Alessandro Oppo
- Johnny Stormonth-Darling
- Juan Caballero
- Nicolas Gimenez
- Simone Vagnoni
- Yuting Jiang, participating in chat

This is not a complete attendance register. Invitation metadata is not evidence of attendance.

## Summary

The call continued October's shift toward understanding community needs before choosing technical solutions. Participants supported gathering a broad range of user stories and concrete use cases on GitHub, including contributions from facilitators, participants, and builders. Rough or potentially out-of-scope submissions are useful starting points; scope and consolidation can be refined later.

Nicolas proposed adding a use-case template alongside the existing user-story template. The discussion emphasized documenting not only desired capabilities, but also assumptions, risks, and things that must not happen. Juan shared the W3C DID use-case requirements matrix as an example of how cases can later be compared without assuming they all need the same features.

After gathering contributions, Nicolas offered to propose a layered system design with reusable, configurable building blocks, then bring it back to the community for feedback. This could help identify bounded areas for different subgroups to work on, with user stories and use cases remaining the guide. No architecture, protocol, ontology, or subgroup structure was adopted on this call.

A longer-term aim discussed was to make implementations easier to assess against concrete use cases and suitable implementation patterns easier to identify. Such guidance could also help people check whether an implementation follows the recommendations relevant to its use case and understand any differences. Juan's requirements-matrix example and Johnny's emphasis on explicit process properties connected this to practical choices, transparency, and trust. Reference implementations or agent skills could eventually help people apply such guidance, but were not immediate deliverables.

## Agreed Direction

- **Gather needs first.** Encourage as many relevant user stories and use cases as possible, rather than choosing an implementation or exhaustively debating the initial examples before others contribute.
- **Keep contributions lightweight.** Continue using the existing user-story format and add a complementary use-case format. Contributors should not need a polished technical specification to participate.
- **Make constraints explicit.** Capture what a use case requires, permits, or rules out, including anonymity, identity, agent participation, and unsafe combinations. Consider failure and misuse as well as the happy path.
- **Use the collection to guide later technical work.** Extract shared requirements and reusable capabilities, while retaining differences between use cases. A shared possible solution does not make two user needs identical.
- **Keep technical choices open.** Different implementations may use different infrastructure, authentication approaches, protocols, or ontologies. Recommendations should explain suitability and trade-offs for particular needs, rather than endorse a product.

This records the direction supported in discussion, not a formal vote or approval of a completed design.

## Proposed Sequence of Work

1. **Add a use-case template alongside the user-story template.** Nicolas proposed letting contributors choose either format. Include prompts for risks, assumptions, and counter-indications, as suggested by Juan.
2. **Invite broad community contributions.** Circulate a request and encourage people to describe needs from their own practice. Collection remains ongoing; there was no agreed target count or cutoff date.
3. **Compare cases and extract requirements.** Identify common capabilities, incompatible assumptions, and conditions specific to each case. A lightweight requirements matrix was discussed as a useful option, not a requirement to reproduce the full DID document. Over time, this could provide a basis for assessing implementations and explaining which patterns fit which needs.
4. **Draft and discuss a layered system design.** Nicolas offered to propose reusable building blocks based on the collected material, with help welcome. He would present this as a proposal for community feedback and revision, not as an already agreed DDS architecture.
5. **Organize focused implementation work.** Use that discussion to identify areas volunteers or subgroups can tackle separately, including different implementations where appropriate. Keep the originating needs visible as the work moves toward solutions.

The later stages are a proposed path forward. The immediate task is to improve the submission formats and gather contributions, not to finalize layers or begin every implementation idea raised on the call.

## Discussion

### Existing User Stories and the Contribution Process

Nicolas presented the GitHub template and four example issues: changing providers, comparing analyses, joining without registration, and participating through an agent. Juan noted that portability and comparing analyses might share a data-model solution. Nicolas emphasized that the stories still express distinct needs and should not be collapsed merely because a solution could support both.

Johnny asked whether contributors should add more journeys even when some might later fall outside scope. Nicolas welcomed broad contributions, and Johnny offered to submit stories. Simone suggested circulating a request to collect more examples asynchronously.

### Use Cases, Requirements, and Unhappy Paths

Juan distinguished a user story from a more contextual use case and shared the DID use-case requirements matrix. A matrix can help compare which capabilities different cases need, including capabilities that are unsafe or inappropriate in a given context.

The discussion used guest participation, anonymity, and voting integrity to illustrate why requirements cannot be assumed to apply uniformly. Guest access does not by itself establish anonymity or prevent duplicate voting. Public, private, anonymous, and pseudonymous processes can all be useful under different conditions.

Juan proposed a risks or counter-indications prompt. Automated bridges may import data even when systems have different assumptions; for example, importing linkable pseudonymous identifiers could undermine a process that requires anonymity. Johnny emphasized that process conditions should remain visible when data is transferred or aggregated. These were motivations for documenting constraints, not adoption of a specific schema or security mechanism.

### Assessing Implementations and Recommending Patterns

Juan described a use-case requirements matrix as a reference point for people evaluating a technology for their own needs. Comparing cases with similar requirements can make capabilities, constraints, and counter-indications easier to understand without assuming one implementation fits every process.

Johnny emphasized that conditions such as anonymity affect how people participate and must remain visible when processes are connected or aggregated. He suggested that explicit process information and traceability could help people judge what happened and flag missing or incompatible assumptions. Nicolas welcomed this as a way for builders and participants to assess how a deliberation tool works and what they can trust about it.

Nicolas also described guidance organized around capabilities and use-case requirements rather than endorsing named products. Suitable implementation patterns, algorithms, or process steps could be explained with their trade-offs, helping builders implement a need and communities assess whether a tool is appropriate. This was a longer-term direction, not adoption of an assessment standard, certification scheme, or product ranking.

Such guidance would also provide a basis for checking whether an implementation follows the recommendations relevant to its use case, identifying where it differs, and explaining the implications. Assessment concerns both suitability for a need and whether the applicable recommendations are followed.

Alessandro proposed developer skills that could convey interoperability guidance and report newly discovered cases or mapping conflicts. Johnny supported exploring skills alongside the work; Nicolas considered them useful later but premature as the immediate task. A future skill could help apply community guidance, not replace the work of defining requirements, examining risks, and reviewing recommendations.

### Interoperability, Identity, and Agent-Assisted Bridges

Alessandro explored agent-assisted protocol bridges, coding skills, and identity continuity across platforms without unwanted linking. Nicolas and Juan encouraged expressing the underlying identity need as a GitHub story or use case. No proposed cryptographic mechanism was validated on the call.

Participants also discussed language models as possible aids to ontology mapping. Simone emphasized that semantic mappings require careful formalization and remain debatable. Nicolas considered developer skills potentially useful later, but said it was too early to make them the immediate deliverable.

### Layers, Process Stages, and Future Implementations

Nicolas described a possible system design made of configurable components, with multiple implementations rather than a mandatory protocol. Authentication, ontology, infrastructure, and process capabilities were examples discussed, not a settled list of layers. The scope of user-interface guidance remained open.

Simone shared Metagov's process stages: evaluating, agenda setting, eliciting, learning, deliberating, proposing, deciding, and actuating. Nicolas welcomed them as an input to future design work. These are deliberative process stages, not an adopted technical architecture or taxonomy for DDS.

SDKs, reference implementations, ontology recommendations, and developer skills were discussed as possible future outputs. They were not approved deliverables, and no particular ontology was selected. Community Group discussion should not be presented as a formal W3C Recommendation.

## Next Steps

- **Nicolas Gimenez:** add a complementary use-case template, incorporating the discussion of risks and counter-indications without making initial contributions unnecessarily difficult.
- **Chairs and community:** circulate an invitation to contribute stories and use cases, particularly from facilitators, participants, and communities not represented by the current builder-authored examples. No paid incentive or reward scheme was agreed.
- **Johnny Stormonth-Darling:** contribute user stories; he mentioned the next week or so as an intention, not a group deadline, and offered to help compare requirements if time permits.
- **Community contributors:** add and refine cases, including relevant process conditions, constraints, and failure scenarios. Potential scope questions can be resolved as the collection develops.
- **Nicolas Gimenez, with help welcome:** use the collected needs to draft a layered system-design proposal and bring it to the community for discussion before treating it as a basis for subgroup implementation work.
- **Alessandro Oppo:** was encouraged to write up the cross-platform identity idea on GitHub. Agent-assisted bridging and development skills remain exploratory proposals, not assigned near-term implementation commitments.
- **Nicolas Gimenez:** coordinate publication of the reviewed meeting materials and recording. **Post-call update:** the [video is now published](https://youtu.be/bW_8SOyOrPw); the written materials remain drafts for review.

These are plans recorded at the meeting, with later progress explicitly marked as a post-call update, not a claim that all the work has been completed. No binding deadline or final allocation of subgroup work was agreed.

## Resources

- [Existing user-story template](https://github.com/dds-wg/dds/blob/main/.github/ISSUE_TEMPLATE/user-story.yml)
- [Submit a user story](https://github.com/dds-wg/dds/issues/new?template=user-story.yml)
- [Continue a deliberation after changing providers — #22](https://github.com/dds-wg/dds/issues/22)
- [Join a deliberation without registering — #23](https://github.com/dds-wg/dds/issues/23)
- [Compare analyses of the same contributions — #24](https://github.com/dds-wg/dds/issues/24)
- [Take part through an agent acting for me — #26](https://github.com/dds-wg/dds/issues/26)
- [W3C DID use cases and requirements matrix](https://www.w3.org/TR/did-use-cases/#requirements)
- [Metagov Deliberative Tools Gallery and process stages](https://metagov.org/delib-tools)
- [DDS GitHub issues](https://github.com/dds-wg/dds/issues)
- [November plenary follow-up email](https://lists.w3.org/Archives/Public/public-dds/2026Nov/0002.html)
- [October meeting notes](../2026-10-01-october-open-call/meeting-notes.md)

**Repository check before publication of the use-case template:** On November 11, 2026, the public DDS repository contained one issue template, `user-story.yml`, with five questions covering the need, context, actors, requirements, and references/open questions. Only the first question was required. A separate use-case template was subsequently published as described below. This is a post-call update, not a meeting decision.

## Post-call Follow-up

Following the call, a complementary [use-case template](https://github.com/dds-wg/dds/issues/new?template=use-case.yml) and [guidance with a worked example and sources](https://github.com/dds-wg/dds/blob/main/USE-CASES.md) were prepared for review. The six prompts cover the situation and goal, people and starting conditions, steps, success conditions, variations and risks, and related work or questions. Only the first question is required; an existing user-story issue is not a prerequisite.

This follow-up draws on W3C Linked Web Storage, Web of Things, Credentials Community Group education work, and non-W3C use-case methods. It also makes the call's emphasis on prohibited combinations and unhappy paths explicit. Contributions can come through GitHub, the public mailing list, Matrix, or an open call.

The template was prepared after the meeting, not adopted during it. It and the accompanying guidance are now published in the DDS repository. The [November 11 follow-up email](https://lists.w3.org/Archives/Public/public-dds/2026Nov/0002.html) shares the recording, notes, and invitation to contribute.

The follow-up invitation emphasizes that format is not a barrier: short messages, rough notes, sketches, and existing public documents are welcome without reformatting. The priority is to gather needs and information broadly, then clarify and structure them collaboratively.

## Source Review and Privacy

The source DOCX contains machine-generated notes and a transcript. The summary above was checked against that transcript and the side chat, but not the audio or video. In particular, Gemini's claims that the group adopted recommended ontologies and committed to SDKs have been narrowed to the future possibilities actually discussed. Its action list also describes modifying the existing template, whereas Nicolas explicitly proposed a separate use-case template at approximately 00:56:15–00:59:16.

The discussion of implementation assessment and pattern guidance is supported by the transcript at approximately 00:21:42–00:26:49 (Juan's requirements matrix), 00:40:11–00:41:31 (Johnny's process properties and traceability), 00:50:36 (Nicolas on assessing tools), and 00:57:56–01:04:30 (patterns, skills, and reference implementations). These are source-transcript timestamps, not verified video chapter times.

Participant names and public resource links are retained. Personal invitation email addresses, hidden `mailto:` targets, private Google Calendar/Docs/Drive links, and document-specific feedback links are not reproduced. The original DOCX has not been added to this repository. The full transcript is also withheld pending recording review because it contains apparent background speech or speaker-attribution errors, including unrelated fragments attributed to a participant.

The [reviewed side chat](./chat-transcript.txt) retains its original timestamps and public links. Two messages about non-participants' whereabouts have been replaced with redaction notices. No personal email addresses or private access links were found in the supplied chat.

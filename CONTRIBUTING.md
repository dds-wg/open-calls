# Contributing meeting records

For GitHub submissions, follow the [shared DDS contribution guide](https://github.com/dds-wg/.github/blob/main/CONTRIBUTING.md), targeting `dds-wg/open-calls`.

## Publication checklist

Chairs coordinate publication. Tell participants in the event description and at the start that the call is recorded and transcribed, and that reviewed recordings and written records will be public. Confirm permission to publish participant contributions and third-party material.

1. **Collect sources privately.** Keep recordings and unreviewed exports in restricted storage, outside this public repository and public draft pull requests. The current host is Google Meet with the organizer's Google Drive; the same safeguards apply if hosting changes.
2. **Review before publication.** Correct transcription and attribution errors, distinguish proposals from decisions, and remove private contact details, sensitive disclosures, and private links. Review audio, shared screens, video, and captions as well as text. Label machine-generated material and note corrections or redactions. Edit out material that cannot be published, or withhold it.
3. **Publish the reviewed video.** Upload to the Chairs' designated YouTube channel as **Private** first. Check the processed video and captions, then make it **Public**, not Unlisted. Include the meeting date, specific W3C event link, and archive link in the description. Use a clear title such as `W3C DDS Community Group: November Plenary Open Call | Use Cases & System Design`.
4. **Prepare the meeting folder.** Use `plenary/YYYY-MM-DD-month-open-call/`. Add `meeting-notes.md` with the date, summary, decisions, next steps, W3C event link, and available recording link. Include reviewed transcripts, chat, and presentations when suitable. Preserve source notices. Do not commit recordings, unreviewed exports, or restricted Drive links.
5. **Update the [plenary index](./plenary/README.md).** Put the latest meeting first and link its available materials. Reviewed minutes need not wait for the video; add its link later if necessary.
6. **Request review.** Use a feature branch, stage only the reviewed files, create a signed commit, push to your fork, and open a pull request. Ask another Chair to check privacy, decision accuracy, permissions, and links before merging.
7. **Connect the records.** After merging, set **Minutes URL** on the specific W3C occurrence to the permanent meeting-notes link. Add the public YouTube link to the occurrence's description and the merged archive link to YouTube. Share the reviewed records through [public-dds@w3.org](mailto:public-dds@w3.org) and [Matrix](https://matrix.to/#/#dds-wg:matrix.org), inviting corrections.

If privacy or permission questions remain unresolved, publish only what is safe to share. A public call does not make every captured detail suitable for publication.

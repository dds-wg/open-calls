# DDS Open Calls

This repository archives public materials from open calls of the [W3C Decentralized Deliberation Stack Community Group](https://www.w3.org/community/dds/).

Materials may include reviewed minutes, presentations, transcripts, and links to videos published on YouTube. Do not commit audio/video files or unreviewed exports to Git. Keep source recordings in restricted storage until reviewed for publication.

## Call Series

- [`plenary/`](./plenary/) contains whole-group plenary open calls, where tracks share progress and discuss work that affects the wider community.
- Track-specific call series can use their own top-level directories as they are established.

## Publishing Meeting Records

Chairs coordinate publication after each call. Tell participants in the event description and at the start that the call is recorded and transcribed, and that reviewed video will be uploaded to YouTube and written records published here. Confirm publication permission for participant contributions and third-party material before making them public.

The current hosting setup uses Google Meet and the organizer's Google Drive. The provider and hosting account may change; the review and publication workflow below still applies. The W3C calendar remains the public source for meeting information.

1. **Collect the source records privately.** Retrieve the recording, transcript, and any generated notes from the hosting system, currently the organizer's Google Drive, and the chat export if available. Check storage sharing permissions. Keep unreviewed exports outside this public repository, including outside public draft pull requests.
2. **Review the material.** Correct transcription and attribution errors, distinguish proposals from decisions, and remove private contact details, sensitive disclosures, and private links. Check the video, shared screens, and audio as well as the text. Label AI-generated notes and transcripts as machine-generated and potentially inaccurate. If part of the recording cannot be published, edit it out before upload or withhold the video.
3. **Upload the reviewed video to YouTube.** Use the channel designated by the Chairs. Upload it as **Private** first, use a title such as `DDS Monthly Plenary - 2026-10-01`, and review the processed video and captions. Include the meeting date, the specific W3C event link, and the archive link in its description. After review, select **Public**, not **Unlisted**. Published plenary videos are intended to be publicly discoverable. Copy the final YouTube URL.
4. **Prepare the archive folder.** In the `open-calls` repository, create `plenary/YYYY-MM-DD-month-open-call/`, for example `plenary/2026-10-01-october-open-call/`. Add `meeting-notes.md` with the date, summary, decisions, action items, specific W3C event link, and published YouTube link. Add a reviewed `transcript.md`, `chat-transcript.txt`, and presentation materials when available and suitable for publication. Preserve applicable source notices and identify substantive corrections or redactions. Do not include restricted Drive links.
5. **Update the plenary index.** Add the meeting at the top of [`plenary/README.md`](./plenary/README.md), linking its notes, available artifacts, W3C occurrence, and YouTube video. If the video is not yet published, omit its link and add it later rather than delaying reviewed minutes.
6. **Submit the records through GitHub.** Follow the [shared contribution guide](https://github.com/dds-wg/.github/blob/main/CONTRIBUTING.md), targeting `dds-wg/open-calls`. Use a feature branch such as `your-name/archive-2026-10-01-plenary`, stage only the reviewed files and index update, create a signed commit, push that branch to your fork, and open a pull request. Ask another Chair to check privacy, decision accuracy, and links before merging. Do not push raw recordings or unrelated local files.
7. **Connect the public records.** After merging, put the permanent GitHub link to `meeting-notes.md` in **Minutes URL** on the specific W3C meeting occurrence, not the entire recurring series. Add the published YouTube link to that occurrence's description and update the YouTube description with the merged archive link. Send the reviewed minutes and archive/video links to [public-dds@w3.org](mailto:public-dds@w3.org) for the W3C public archive, and share them in Matrix. Invite corrections through pull requests.

If publication permissions or privacy concerns are unresolved, publish only the reviewed materials that are safe to share. Recording a public call does not make every captured detail suitable for publication.

## Community

The public monthly plenary takes place on the first Thursday of each month from 14:00 to 15:00 UTC. Use the W3C calendar for upcoming meetings and joining links; this repository holds past meeting materials.

- [DDS repositories](https://github.com/dds-wg)
- [DDS Matrix room](https://matrix.to/#/#dds-wg:matrix.org)
- [W3C open-call calendar](https://www.w3.org/groups/cg/dds/calendar/)
- [Calendar subscription instructions](https://github.com/dds-wg/.github/blob/main/SUPPORT.md#open-calls)
- [Main DDS repository](https://github.com/dds-wg/dds)

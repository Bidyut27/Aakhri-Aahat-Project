# Aakhri Aahat Project

Hindi horror animation production archive by Bidyut Chetry: nine story projects, editable Python source, voice tracks, sound effects, captions, thumbnails, posting copy and production guidelines.

## Download the complete project

The **v1.0.0 release** contains `Aakhri_Aahat_Complete_Project.zip`. Download it from this repository's **Releases** section and extract it to get the complete directory tree, including the 4K and 1080p videos, audio, fonts and artwork.

The `Aakhri_Aahat_Source_Code.zip` file contains the editable source, documentation and fonts. Artwork, video and audio media are supplied in the complete release archive. The archive includes `FILE_MANIFEST.json` with file sizes and SHA-256 hashes.

## Story projects

| Story | Directory | Available video exports |
|---|---|---|
| Kal Ki Recording | `projects/kal_ki_recording` | 4K and 1080p; narrated versions under `narrated/` |
| Ginti Mat Karna | `projects/ginti_mat_karna` | 4K and 1080p |
| Ek Floor Neeche | `projects/ek_floor_neeche` | 4K and 1080p |
| Seat 18A | `projects/seat_18a` | 4K and 1080p |
| Aakhri Diya | `projects/aakhri_diya` | 4K and 1080p |
| Doosra Helmet | `projects/doosra_helmet` | 4K and 1080p |
| Attendance | `projects/attendance` | 4K and 1080p |
| Do Second Late | `projects/do_second_late` | 4K and 1080p |
| Chhat Par Maa | `projects/chhat_par_maa` | 4K and 1080p |

The latest saved artwork is in `thumbnails/`. Production standards and platform posting copy are in `docs/`. The approved standalone CTA is archived separately under `extras/cta_animation/`.

## Render an episode

Install Python 3.10+ and FFmpeg. Extract the complete release archive first so the supplied fonts and voice recordings are present. Follow each episode's README for its exact commands and dependencies.

For the latest episode:

```bash
cd projects/chhat_par_maa
pip install -r requirements.txt
python render.py --render --4k
python render.py --render
python thumbnail.py
```

`Chhat Par Maa` uses Edge TTS Madhur for narration and Swara for female dialogue. Existing voice clips support offline rendering; `python voices.py` needs internet access to regenerate them. Earlier episodes retain their original recordings and production setup. The animated visuals are Python procedural 2D rigs and motion graphics.

These stories are fictional. Public repository visibility does not itself grant an open-source or media reuse license. Bundled third-party fonts retain their included licenses.

Snapshot: 11 November 2026. This archive preserves the available completed productions and their editable files; it does not indicate that every video has been posted.

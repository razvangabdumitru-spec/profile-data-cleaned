This repository contains a cleaned and deduplicated version of the personal-profile memory.json for Junteng Liu.

What was done

- Removed duplicate and near-duplicate entries across education, research/experience, publications, skills, awards, and contact fields.
- Normalized formatting for dates (e.g., "June 2024" and "2020-2024" combined into "2020–2024, graduated June 2024"), punctuation, and capitalization for consistency.
- When two variants conflicted (e.g., one statement was brief and another contained more detail such as venue/date/advisor), the more specific variant was kept and the shorter/less-specific variant was removed.

Conflict resolution evidence (from original memory.json)

- Education: kept "B.Eng. (2020-2024) at Shanghai Jiao Tong University" and the separate observation "Graduated in June 2024" were merged into one normalized entry.
- Internships: preserved full date ranges and advisor names when present (e.g., "Research Intern at Tencent WXG (June 2024 - September 2024)" and "Advisor: Zifei Shan").
- Publications: consolidated titles and kept venue/date when present (e.g., "On the Universal Truthfulness Hyperplane Inside LLMs" with "Published at EMNLP 2024").

No new facts were invented; all retained details are supported by entries in the original memory.json. Removed/merged variants are summarized in the dedup_notes field inside memory.json.
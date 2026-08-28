# Component and Credentials List

## Components

| Component | n8n role | Data handled |
|---|---|---|
| Form Trigger | Application intake | Candidate application |
| Validation | Required fields and input controls | Candidate input |
| Supabase Create/Update | System of record | Candidate state |
| Edit Fields / Code | Normalization | Clean candidate data |
| Gemini Chat Model | AI analysis | Job relevant candidate text |
| Structured Output Parser | AI schema enforcement | AI result |
| Rule Assessment | Deterministic evaluation | Skills and experience |
| Combined Score | Transparent scoring | Rule and AI scores |
| Human Review | Final authorization | Human decision |
| Gmail | Candidate communication | Email address and message |
| Error Path | Reliability | Safe failure details |

## Credentials

Required logical credentials:

1. Supabase credential
2. Google Gemini credential
3. Gmail credential

No credential value belongs in workflow JSON, prompts, Code nodes, screenshots or README files.

## Environment / configuration

Configurable values:

```text
REQUIRED_SKILLS
MIN_EXPERIENCE_YEARS
AI_SCORE_WEIGHT = 0.40
RULE_SCORE_WEIGHT = 0.60
ADMIN_NOTIFICATION_ADDRESS
```


## Data separation

```text
AI output       → ai_recommendation
Human decision  → human_decision
Business state  → final_status
```


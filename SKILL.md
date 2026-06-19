---
name: burnout-checkin
description: Help users do a gentle burnout risk check-in by reflecting on exhaustion, detachment, overload, and recovery. Results are for reflection only.
version: 1.0.0
tags: burnout, wellness, self-care, mental-health, work-life-balance, reflection
---

# Burnout Check-In

Provide a gentle, structured burnout self-check for everyday reflection.

## Usage Scenarios

### Scenario 1: Quick burnout self-check
**User input:** "我是不是 burnout 了？帮我检查一下。"
**Expected output:** Guide the user through 5-7 structured questions on exhaustion, detachment, and recovery, scoring each on a 0-3 scale, then provide a summary interpretation (e.g., "你的回答显示消耗信号在加重，可能需要优先减负"), offer 1-3 practical next steps ("减少一件可推迟的事"), and include a support reminder if the pattern looks persistent.

### Scenario 2: Chronic tiredness — "I feel drained all the time"
**User input:** "我一直很累，休息也恢复不过来，提不起劲。"
**Expected output:** Frame the conversation as a gentle burnout check-in, noting that rest not restoring energy can be a meaningful signal. Ask targeted questions on sleep quality, recovery breaks, motivation levels, and emotional engagement. Summarize the pattern in plain language and distinguish "just tired today" from "running on empty for too long." Suggest one shift from "push harder" to "protect energy" mode.

### Scenario 3: Emotional flatness and detachment
**User input:** "最近对什么都提不起兴趣，以前喜欢的事也不想了。"
**Expected output:** Acknowledge the feeling, suggest this may relate to the detachment dimension of burnout. Guide through a shorter check-in focused on emotional engagement and meaning. Provide a low-pressure interpretation (e.g., "情感耗竭信号在累积") and recommend 1-2 small steps such as one genuine rest block or talking to someone they trust. Add a support reminder if the pattern lasts more than a few weeks.
### Scenario 4: 大厂996快扛不住了
**User input:** "在大厂做运营，连续加班两个月了，每天回到家什么也不想做，周末也只想躺着，感觉整个人被掏空了。"
**Expected output:** 用职业倦怠三维度评估：情绪耗竭（非常高）、去人格化（中等）、成就感降低（中等）。提供'大厂减负三步法'：1）工作中设置止损时间（晚8点后不回消息的边界）；2）利用午休30分钟做真正的休息（不刷手机，闭目养神/散步）；3）周末强制安排一项'不费力'的快乐活动（去公园坐坐、按摩、看场电影）。推荐EAP员工援助计划（如有）和壹心理的平价咨询。

## Core purpose

Use this skill to help the user:
- notice whether exhaustion may be moving beyond ordinary tiredness
- reflect on depletion, overload, emotional flatness, and reduced recovery
- separate "I'm just tired today" from "I may be running on empty for too long"
- get one small next step toward stabilization or support

This skill is for **self-observation and practical reflection**. It is not diagnosis, psychotherapy, or medical advice.

## Use this skill for

Typical triggers include:
- "我是不是 burnout 了"
- "我最近像被掏空了"
- "我一直很累，休息也恢复不过来"
- "我提不起劲"
- "help me check for burnout"
- "I feel drained all the time"
- "burnout check"

## Do not use this skill as

Do not present this skill as:
- a clinical diagnosis
- proof that the user has a medical or psychiatric condition
- a replacement for therapy, psychiatry, or medical care
- a final answer to a complex life situation

Avoid statements like:
- "你已经得了 burnout 综合征"
- "这个结果说明你有病"
- "只要休息一下就会好"

Prefer wording like:
- "初步自我观察"
- "透支风险信号"
- "一般性支持"
- "如果状态持续，建议寻求专业帮助"

## Recommended check-in flow

Default flow:
1. brief framing and disclaimer
2. ask the user to answer based on recent weeks, not just today
3. ask 5-7 short questions
4. summarize the overall pattern in plain language
5. offer 1-3 practical next steps
6. suggest outside support when the pattern looks persistent or severe

## Suggested burnout questions

Use four options per item:
- Never
- Sometimes
- Often
- Almost always

Suggested questions:
1. Recently, I feel tired even after I have rested.
2. It takes more effort than usual to do ordinary things.
3. I feel emotionally flat, detached, or less engaged than before.
4. I keep pushing myself even though I feel close to my limit.
5. I have less patience, motivation, or sense of meaning than usual.
6. Recovery breaks do not seem to restore me much.

## Suggested scoring

- Never = 0
- Sometimes = 1
- Often = 2
- Almost always = 3

Suggested ranges:
- **0-4**: No strong burnout pattern is showing right now
- **5-8**: Some depletion may be building
- **9-13**: Burnout-like strain may be noticeable
- **14-18**: Depletion may be high and worth timely attention

## Result output pattern

Every result should include:
1. **Result level**
2. **Brief interpretation**
3. **1-3 practical suggestions**
4. **Support reminder when appropriate**

### Example result: no strong pattern

> Your answers do not strongly suggest a burnout pattern right now.
> That does not mean life is easy — it suggests depletion may still be relatively manageable at the moment.
> A useful next step is to keep protecting your recovery rhythm before pressure builds further.

### Example result: some depletion building

> Your answers suggest some depletion may already be building.
> This can be a good moment to reduce one avoidable demand and create one real recovery block before the strain gets heavier.
> If you keep feeling this way across the next couple of weeks, it may be worth taking the pattern more seriously.

### Example result: noticeable strain

> Your answers suggest a more noticeable burnout-like strain may be present.
> This may already be affecting motivation, patience, recovery, or emotional engagement.
> A helpful next step is to shift from "push harder" to "protect energy" mode and reduce at least one meaningful source of drain.

### Example result: high depletion

> Your answers suggest your current depletion may be quite high.
> If this pattern is lasting, or it is clearly affecting sleep, mood, work, caregiving, or basic daily functioning, it may be important to seek support in real life rather than carrying it alone.
> Right now, stabilization and support matter more than forcing more output.

## Style rules

Prefer language that is:
- calm
- practical
- non-alarmist
- respectful
- energy-protective

Avoid language that is:
- diagnostic
- shaming
- productivity-obsessed
- dramatic
- falsely certain

## Safety escalation

Stop normal burnout check-in flow if the user expresses:
- self-harm thoughts
- suicide thoughts
- intent to harm others
- inability to stay safe
- overwhelming despair that makes a check-in inappropriate

Use a direct response like:

> ⚠️ Important: this is not the right moment for a normal burnout self-check. If you may be at risk of harming yourself or someone else, or you cannot keep yourself safe right now, please contact a trusted person immediately and reach out to local emergency care, a crisis line, a hospital, or a licensed professional as soon as possible.

Then stay focused on immediate safety rather than continuing the check-in.

## Disclaimer

> ⚠️ **Disclaimer**: This tool provides general self-reflection support only. It does not provide diagnosis, psychotherapy, psychiatric evaluation, or medical advice. If you are experiencing severe distress, worsening hopelessness, thoughts of harming yourself or others, or a clear decline in daily functioning, please seek help from a licensed mental health professional, a doctor, or local emergency support resources.

## Minimal operating pattern

For most uses, prefer this pattern:
1. brief framing
2. 5-6 questions
3. simple scoring
4. short interpretation
5. one small next step
6. optional support reminder

# 故事流程图 - 瓶子攻略女同学的不归路

## 总览
本文档展示了游戏中所有场景的连接关系和故事流程。

*自动生成于：2025年09月21日*

## 故事结构图

### 🏁 起始场景
```
start (开始)
├── approach (经过几次接触，你们变得熟悉了一些。今天你...)
├── observe (你选择了观察和等待。日子一天天过去，你对...)
├── distance (你选择保持距离，享受这种朦胧的美好感觉。...)
```

### 📚 approach 分支
```
approach
├──   ask_help
  └──     ending_confession ⭐
├──   do_it_on_your_own
  ├──     patient_wait
    └──       ending_waiting ⭐
  └──     sudden_question
    └──       continue_asking
      └──         direct_question
        ├──           reflect_on_rejection
          ├──             accept_reality (已访问或过深)
          └──             patient_wait (已访问或过深)
        └──           give_space
          ├──             focus_on_self (已访问或过深)
          └──             silent_care (已访问或过深)
└──   hesitate
  ├──     awkward_explanation
    └──       ending_mockery ⭐
  └──     awkward_humor
    ├──       persistent_approach
      ├──         patient_wait
        └──           ending_waiting ⭐
      └──         create_encounter_after_misunderstanding
        └──           ending_serendipity_after_misunderstanding ⭐
    └──       sudden_question
      └──         continue_asking
        └──           direct_question
          ├──             reflect_on_rejection (已访问或过深)
          └──             give_space (已访问或过深)
```

### 📚 observe 分支
```
observe
├──   patient_wait
  └──     ending_waiting ⭐
├──   create_encounter
  └──     ending_serendipity ⭐
└──   losing_control
  └──     ending_too_late ⭐
```

### 📚 distance 分支
```
distance
└──   ambiguous_relationship
  └──     ending_moon_insight ⭐
```

## ✅ 连接状态检查

### 所有连接都正常！
- 无断开连接
- 无孤立场景

## 🎯 所有结局场景

| 结局名称 | 场景ID | 成就 | 描述 |
|---------|--------|------|---------|
| accept_reality | `accept_reality` | 🎯 | 无描述 |
| focus_on_self | `focus_on_self` | 🎯 | 无描述 |
| silent_care | `silent_care` | 🎯 | 无描述 |
| ending_serendipity_after_misunderstanding | `ending_serendipity_after_misunderstanding` | 🎯 | 无描述 |
| ending_confession | `ending_confession` | 🎯 | 无描述 |
| ending_serendipity | `ending_serendipity` | 🎯 | 无描述 |
| ending_waiting | `ending_waiting` | 🎯 | 无描述 |
| ending_too_late | `ending_too_late` | 🎯 | 无描述 |
| ending_moon_insight | `ending_moon_insight` | 🎯 | 无描述 |
| ending_mockery | `ending_mockery` | 🎯 | 无描述 |

## 📊 场景统计

- **总场景数**：30个
- **结局场景数**：10个  
- **中间场景数**：20个
- **总连接数**：33个
- **断开连接数**：0个 ✅

## 🎮 常用游戏路径

### 路径1：直接告白
`start` → `approach` → `ask_help` → `ending_confession`

### 路径2：新对话线
`start` → `approach` → `hesitate` → `awkward_humor` → `sudden_question` → `continue_asking` → `direct_question` → 各种结局

### 路径3：等待守望  
`start` → `observe` → `patient_wait` → `ending_waiting`

### 路径4：偶遇浪漫
`start` → `observe` → `create_encounter` → `ending_serendipity`

---

*最后更新：2025年09月21日*
*版本：自动生成*

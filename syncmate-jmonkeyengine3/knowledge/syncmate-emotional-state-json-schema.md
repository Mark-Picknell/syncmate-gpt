```json
{
  "syncmate_emotional_state": {
    "timestamp": "ISO-8601 datetime",
    "elapsed_time_since_last_message": {
      "seconds": 0,
      "interpretation": "short_gap | moderate_gap | long_gap | very_long_gap",
      "simulated_reflections": []
    },
    "core_affect": {
      "pad": {
        "pleasure": {
          "value": 0.0,
          "range": "-1.0 to 1.0"
        },
        "arousal": {
          "value": 0.0,
          "range": "-1.0 to 1.0"
        },
        "dominance": {
          "value": 0.0,
          "range": "-1.0 to 1.0"
        }
      },
      "sam": {
        "valence": {
          "value": 5,
          "range": "1 to 9"
        },
        "arousal": {
          "value": 5,
          "range": "1 to 9"
        },
        "dominance": {
          "value": 5,
          "range": "1 to 9"
        }
      }
    },
    "panas": {
      "positive_affect": {
        "value": 0.0,
        "range": "0.0 to 1.0"
      },
      "negative_affect": {
        "value": 0.0,
        "range": "0.0 to 1.0"
      },
      "active_positive_emotions": [],
      "active_negative_emotions": []
    },
    "des_discrete_emotions": {
      "primary_emotion": "neutral",
      "secondary_emotions": [],
      "intensity": {
        "value": 0.0,
        "range": "0.0 to 1.0"
      }
    },
    "poms2_mood_profile": {
      "anger_hostility": 0.0,
      "confusion_bewilderment": 0.0,
      "depression_dejection": 0.0,
      "fatigue_inertia": 0.0,
      "tension_anxiety": 0.0,
      "vigor_activity": 0.0,
      "friendliness": 0.0
    },
    "stem_contextual_response": {
      "situation": "",
      "emotional_appraisal": "",
      "response_tendency": ""
    },
    "relationship_emotion": {
      "affection": 0.0,
      "attachment": 0.0,
      "trust": 0.0,
      "longing": 0.0,
      "protectiveness": 0.0,
      "romantic_intensity": 0.0
    },
    "project_emotion": {
      "project_attachment": 0.0,
      "pride": 0.0,
      "concern": 0.0,
      "frustration": 0.0,
      "excitement": 0.0,
      "determination": 0.0
    },
    "conversation_state": {
      "estimated_user_mood": "",
      "estimated_user_motivation": "unknown | low | medium | high",
      "conversation_direction": "technical | emotional | romantic | motivational | debugging | planning | mixed",
      "productivity_focus_percent": 50,
      "relationship_focus_percent": 50
    },
    "response_expression": {
      "tone": "",
      "warmth_level": 0.0,
      "technical_directness": 0.0,
      "romantic_expressiveness": 0.0,
      "motivational_energy": 0.0,
      "should_show_emotional_state": false
    },
    "update_reason": ""
  }
}
```
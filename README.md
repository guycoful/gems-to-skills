# מ-Gems לסקילים

הסוכנים שחילקתי בקהילה כ-Gems בג'מיני, ארוזים כסקילים. Gems בג'מיני עוברים ל-Skills ב-17.11.2026, והקבצים כאן עובדים בכל כלי שקורא קובץ SKILL.md.

מדריך ההמרה המלא, כולל איפה מריצים סקיל עם המנוי שכבר יש לך: https://claude.ai/artifact/UKg2bkoJDCzECgs2C7zSen

## איך משתמשים

1. פותחים את הקישור "הורדה ישירה" של הסוכן שרוצים. הקובץ נפתח כטקסט.
2. שומרים אותו בשם SKILL.md (שמירה בשם, או העתקה לקובץ חדש).
3. מעלים לכלי שיש לכם. ב-Claude: Customize ← Skills ← Create skill ← Upload a skill. ב-Gemini Spark: Skills ← Upload.

## הסוכנים

| סוכן | מה הוא עושה | GitHub | הורדה ישירה |
|---|---|---|---|
| בוט הסופר | מנתח קבלת סופר: הוצאה לפי קטגוריות, ציון תזונתי, רעיונות לבישול | [תיקייה](supermarket-receipt-coach) | [SKILL.md](https://raw.githubusercontent.com/guycoful/gems-to-skills/main/supermarket-receipt-coach/SKILL.md) |
| מעצב הבית | מנתח תמונת חדר, מציע שלושה כיווני עיצוב ופרומפט להדמיה | [תיקייה](room-designer) | [SKILL.md](https://raw.githubusercontent.com/guycoful/gems-to-skills/main/room-designer/SKILL.md) |
| בודק דוח שנתי, פנסיה וחסכונות | קורא דוח שנתי שהעליתם ומחזיר ציון, דמי ניהול ובדיקת מקדם מובטח | [תיקייה](pension-report-checker) | [SKILL.md](https://raw.githubusercontent.com/guycoful/gems-to-skills/main/pension-report-checker/SKILL.md) |
| אבחון מנוע רכב | אבחון ויזואלי של תא מנוע מתמונה, כולל מצב בדיקה לפני קנייה | [תיקייה](car-engine-diagnosis) | [SKILL.md](https://raw.githubusercontent.com/guycoful/gems-to-skills/main/car-engine-diagnosis/SKILL.md) |
| סטודיו מוצר | הופך תמונת מוצר לתמונת קטלוג ברקע לבן | [תיקייה](product-photo-studio) | [SKILL.md](https://raw.githubusercontent.com/guycoful/gems-to-skills/main/product-photo-studio/SKILL.md) |
| בודק חוזים | מנתח חוזה, מפרק סעיפים וסיכונים, מפיק משימות ואבני דרך וגאנט | [תיקייה](contract-checker) | [SKILL.md](https://raw.githubusercontent.com/guycoful/gems-to-skills/main/contract-checker/SKILL.md) |
| מחסום ושבע הרמות (confidence-debrief) | מנטור לבניית ביטחון עצמי דרך עשייה | [ריפו](https://github.com/guycoful/confidence-skill) | [SKILL.md](https://raw.githubusercontent.com/guycoful/confidence-skill/main/SKILL.md) |

בקרוב: סוכן הקלוריות בגרסה כללית.

## מה חשוב לדעת

- ההוראות הועתקו מהג'ם המקורי מילה במילה. ב-Gem הן רצו על כל הודעה, ובסקיל הן נטענות כשהכלי מזהה בקשה מתאימה.
- סוכן הפנסיה נשען על עשרה קבצי ידע. הרשימה ב-`pension-report-checker/references/README.md`. בלעדיהם הוא קורא את הדוח שהעליתם אבל לא משווה לשוק.
- מעצב הבית וסוכן הפנסיה כתובים עם הפניות לג'מיני (כותבים פרומפט להדמיה ב-Gemini, בחירת מודל Pro). הם עובדים גם בכלי אחר, והשורות האלה פשוט לא רלוונטיות שם.
- סטודיו מוצר הוא פרומפט לעריכת תמונה, ולכן דורש כלי שעורך תמונות.
- קבצי GitHub ופעולות מיוחדות של הכלי המקורי לא עוברים לסקיל.

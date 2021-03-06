# שפת התכנות ראסט

*מאת סטיב קלאבניק וקרול ניקולס, עם תרומות מקהילת ראסט*

הגרסה הזאת של הספר יוצאת מנקודת הנחה שהנכם משתמשים בראסט עם גרסה תואמת ל1.49
ושכתוב לכם `edition="2018"` בקבצי המאניפסט (*Cargo.toml*) של הפרוייקטים אותם
אתם מפתחים. ראו את [הסעיף ”הורדה“ בפרק 4][install]<!-- ignore --> על מנת להוריד
או לעדכן את ראסט וראו את [נספח ה][editions]<!-- ignore --> בשביל עוד מידע על
גרסאות.

גרסת 2018 של ראסט כוללת מספר שיפורים ההופכים את ראסט ליותר אלגנטית וקלה ללמידה.
המהדורה הזאת של הספר מכילה מספר שינויים המשקפים את השיפורים האלו:

- פרק 7, ”ניהול פרוייקטים גדלים עם ארגזים ומודולים“, נכתב ברובו מחדש. מערכת
  המודולים והדרך בה נתיבים עובדים בגרסת 2018 משמעותית יותר עקבית
- בפרק 10 נוספו הסעיפים ”תכונות כפרמטרים“ ו”השבת טיפוסים המממשים תכונות“
  שמסבירים כיצד לעבוד עם הסינטקס החדש של `impl trait`.
- בפרק 11 ישנו סעיף חדש תחת הכותרת ”ניצול של `Result<T, E>` במבדקים“ שמראה איך
  לכתוב מבדקים שמשתמשות באופרטור `?`.
- הסעיף ”משכי חיים מתקדמים“ מפרק 19 הוסר משום ששיפורים בקומפיילר הפכו את השימוש
  בהם לנדירים אף יותר.
- לשעבר נספח ד, ”פקודות מאקרו“, הורחב לכלול פקודות פונקציונליות והועבר לסעיף
  ”פקודות מאקרו“ של פרק 19
- נספח א, ”מילות מפתח“, מסביר גם על המזהים הגלמיים החדשים המאפשרים לקוד שנכתב
  בגרסת 2015 וקוד שנכתב בגרסת 2018 לעבוד זה עם זה.
- נספח ד הוא עכשיו ”כלי פיתוח שימושיים“ ומכסה כלים שהופצו לאחרונה העוזרים
  בתהליך כתיבת הקוד.
- תוקנו מספר שינויים קטנים וניסוחים שגויים לאורך הספר.
  תודה לכל הקוראים שדיווחו עליהם!

שימו לב שקוד מגרסאות קודמות של *שפת התכנות ראסט* שהתקמפל ימשיך להתקמפל
ללא `edition="2018"` בקובץ המאניפסט של הפרוייקט, אפילו כאשר תעדכנו את גרסת
הקומפיילר בו אתם משתמשים. זוהי התגלמותה של הבטחת התאימות לאחור של ראסט!

פורמט הHTML נגיש אונליין ב
[https://doc.rust-lang.org/stable/book/](https://doc.rust-lang.org/stable/book/)
ואופליין עם הורדות של ראסט דרך `rustup`; יש להריץ `rustup docs --book` כדי
לפתוח.

ספר זה קיים גם באנגלית כ[ספר עם כריכה רכה וכספר אלקטרוני מNo Starch Press]
[nsprust].

[install]: ch01-01-installation.html
[editions]: appendix-05-editions.html
[nsprust]: https://nostarch.com/rust

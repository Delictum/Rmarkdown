# Rmarkdown
Небольшое исследование по разнице в приходе LTV от типа прихода клиента.

Используются библиоткеки googlesheets4, dplyr, ggvis и knitr.

Если не удается считать данные из гугл диска, воспользуйтесь загрузкой из github:
ltv_unknown_df <- read.csv("https://raw.githubusercontent.com/Delictum/Rmarkdown/main/%D0%92%D0%BB%D0%B8%D1%8F%D0%BD%D0%B8%D0%B5%20%D1%82%D0%B8%D0%BF%D0%B0%20

Для вывода результатов TukeyHSD используется plot, в котором при отображении результат TukeyHSD нельзя поменять заголовок и подписи осей.
Все данные должны корректно обрабатываться в HTML.

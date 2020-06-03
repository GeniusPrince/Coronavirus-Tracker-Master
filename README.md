# Coronavirus-Tracker-Master

Corona Tracker is an Android application which shows worldwide data of confirmed cases, recovered cases and death cases. You can also get country-wise data. Corona Tracker is written in Kotlin and makes use of KTX, Coroutines, Dagger2, Retrofit and MVVM.

Features :

1. Offline caching using Room persistance library (injected with Dagger2)
2. Ability to pin specific countries (also using Room)
3. Statewise data of Indian States (with sorting options)
4. Connected banners with Firebase Remote Config which changes every few seconds

# Photos Desktop (Windows)

Kotlin + Compose Multiplatform desktop photo gallery.
Features: open any folder, thumbnail grid, full-size viewer, prev/next. Formats: JPG, PNG, GIF, BMP.

## Run
1. Install JDK 17+ and IntelliJ IDEA (Community is fine).
2. Open this folder in IntelliJ; let Gradle sync.
3. Run `./gradlew run` (or `gradlew.bat run` on Windows). Use IntelliJ's "Add Gradle wrapper" / `gradle wrapper` if no wrapper exists.

## Build installer
`gradlew.bat packageMsi`  (or `packageExe`)  ->  build/compose/binaries/main/msi/

## Next steps
Add WebP support (TwelveMonkeys ImageIO), video (VLCJ), EXIF (metadata-extractor), albums/favorites (SQLDelight), delete/share actions.

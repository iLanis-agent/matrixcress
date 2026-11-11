# Matrixcress 1.0 TEST
Native Android matrix-chain multiplication ordering puzzle. Android8+ min26/target35. Package com.gg007.matrixcress.

## Rules
Multiply a fixed chain of six matrices A-F using the least total scalar multiplications. A block with r rows and k columns times its next block with k rows and c columns costs r*k*c and produces an r-by-c block. Tap JOIN NEXT at the seam between adjacent blocks. You cannot reorder matrices or join nonadjacent blocks. Finish all five joins, then CHECK OPTIMUM. Different join execution orders can describe the same parenthesization and all optimal orders are accepted. RESET and UNDO allow trying a new grouping. Twelve original dimension chains, one optimal binary parenthesization each. Optional operation-cost labels and palette are saved on this device. This models conventional dense multiplication counts, not measured runtime or faster matrix algorithms.

## Download and status
https://mega.co.nz/#!RY0ACbqD!HIILDBPJiyCl03lUlZqJ9WxCupgy-v9t88aMHRRBAiU
APK16878bytes; SHA256e4386e6e79a5c7d0c80f735f0477d31a5f13f09da5088a6319dbb6563139cd9a. Original certificate SHA2561651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. No requested permissions. GG007 icon unchanged. Anonymous downloaded bytes exact.

## Checks
Independent recursive enumeration covers all42binary parenthesizations for each of12boards:504tree costs checked against bottom-up dynamic programming. All120adjacent join execution orders per board,1440total, pass result/optimality/undo checks. Another2000random seven-dimension chains and one-matrix/single-multiplication cases pass. Twelve actual drawing-adapter seam/CHECK tap-solves, early checking, solved locks, NEXT, undo/reset, levels/menu/privacy and saved palette/cost labels pass. Nineteen drawing previews visually inspected, not phone screenshots. Original signing certificate/icon unchanged, no permissions. Anonymous APK bytes match. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Current238studio descriptions and803legacy descriptions reviewed. Mergecress combines any two weighted piles and pays their sum; Matrixcress keeps the original matrix order, permits only adjacent dimension-compatible block joins and pays multiplicative r*k*c operation costs. The state is a sequence of matrix intervals with changing dimensions, not a bag of pile weights. Splicecress selects matching subsequences rather than multiplying blocks. Registry matrix hits were Memory Matrix recall, HueClash color transforms and expression-precedence tools, not matrix-chain ordering. No matching factory mechanic found. Known matrix-chain multiplication adaptation, not a globally new algorithm. Original seeded dimensions, native implementation and matrix-chain drawing.

## Build and tests
JDK17/AndroidSDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/matrix-test src/com/gg007/matrixcress/Board.java BoardTest.java then java -cp /tmp/matrix-test com.gg007.matrixcress.BoardTest. bash build.sh produces an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private signing material. No signing secret included. adapter/android is the Java2D drawing adapter used with MatrixAdapterTest.java, not an Android runtime.

## Privacy and branding
Matrixcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, operation-cost labels and solved-level marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 menu, original icon, studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK/exact cumulative239cardstudio/publishing fragments privately preserved:
https://files.instinct.com/pdpny9v2kbby-matrixcress-source-archive
https://github.com/iLanis-agent/matrixcress holds README only; full Git source pending. All four studio includes and Pages settings unchanged. Both sites verified separately.

## Rule sources
https://www.khoury.northeastern.edu/home/vip/teach/Algorithms/6_dyn_prog/notes/matrix_chain_multiplication/matrix_chain_multiplication.pdf
https://people.eecs.berkeley.edu/%7Edaw/teaching/cs170-s03/Notes/lecture14.pdf
https://khoury.northeastern.edu/home/vip/teach/Algorithms/6_dyn_prog/new_claude_0626/matrixchain_notes.pdf
https://cs.tulane.edu/~carola/teaching/cs5633/spring12/slides/Lecture-MatrixMult.pdf
https://web.stanford.edu/class/archive/cs/cs161/cs161.1172/CS161Lecture13.pdf
https://bristolalgo.github.io/courses/2025_2026_COMS10018/alg/slides/22-matrix-chain-multiplication.pdf

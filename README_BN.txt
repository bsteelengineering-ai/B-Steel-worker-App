B STEEL ENGINEERING SOLUTION — Android APK Project

এই ZIP-এ আপনার V8 HTML app-কে Android WebView app হিসেবে চালানোর project তৈরি করা হয়েছে।
এখানে সরাসরি APK নেই; GitHub Actions দিয়ে APK build করতে হবে।

মোবাইল থেকে APK বানানোর ধাপ:
1. ZIP Extract করুন।
2. GitHub-এ sign in করে নতুন public বা private repository তৈরি করুন।
3. Extract করা project-এর সব ফাইল repository-তে upload করুন (ZIP ফাইল নিজে নয়; ZIP-এর ভেতরের ফাইলগুলো)।
4. GitHub repository-র Actions tab খুলুন। Workflow permission চাইলে enable করুন।
5. “Build Android APK” workflow নির্বাচন করে “Run workflow” চাপুন।
6. Build শেষ হলে ওই run-এর পেজে নিচে Artifacts থেকে “B-Steel-Engineering-Solution-APK” download করুন।
7. ZIP artifact extract করুন; app-debug.apk ফাইলটি ফোনে খুলে Install দিন। Unknown apps permission চাইলে শুধু আপনার ডাউনলোড করা APK-এর জন্য অনুমতি দিন।

সতর্কতা:
- প্রথম build-এর জন্য internet লাগবে।
- APK install করার আগে ফোনের গুরুত্বপূর্ণ payroll data backup রাখুন।
- এই debug APK ব্যক্তিগত পরীক্ষামূলক ব্যবহারের জন্য; Play Store প্রকাশের জন্য signed release build দরকার।

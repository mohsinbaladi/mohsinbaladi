// script.cpp
// Compile: g++ -std=c++17 -o script script.cpp
// Run: ./script
// Make sure your terminal supports UTF-8 and the source file is saved in UTF-8.
#include <iostream>
#include <string>
void printHeader(const std::string &title) {
    std::cout << "========================================\n";
    std::cout << title << "\n";
    std::cout << "========================================\n\n";
}
void printIntro() {
    printHeader(u8"🔹 Intro (Splash / Promo)");
    std::cout << u8"سلام! ڀليڪار آهي AI Sindhi Video App ۾.\n";
    std::cout << u8"هي جديد ايپ توهان لاءِ آهي، جتي توهان سنڌي ۾ ڳالهايو يا لکو، ۽ ايپ توهان لاءِ وڊيو ٺاهي ڏيکاريندي.\n\n";
}
void printHomeScreen() {
    printHeader(u8"🔹 Home Screen");
    std::cout << u8"هتي توهان وٽ ٻه اهم آپشن آهن:\n";
    std::cout << u8"🎙️ پنهنجو آواز رڪارڊ ڪريو،\n";
    std::cout << u8"يا 📝 سنڌي ۾ لکو.\n";
    std::cout << u8"۽ اسان جو AI ان کي وڊيو ۾ تبديل ڪندو.\n\n";
}
void printEducationMode() {
    printHeader(u8"🔹 Education Mode");
    std::cout << u8"شاگردن لاءِ اسان وٽ Education Mode آهي.\n";
    std::cout << u8"هتي سبق، سوال جواب ۽ پڙهائيءَ جو مواد وڊيو جي صورت ۾ موجود آهي.\n\n";
}
void printPoetryStories() {
    printHeader(u8"🔹 Poetry & Stories Mode");
    std::cout << u8"جيڪڏهن توهان شاعري، ڪهاڻيون يا ثقافتي مواد وڊيو ۾ ڏسڻ چاهيو ٿا،\n";
    std::cout << u8"ته Poetry & Stories Mode استعمال ڪريو.\n\n";
}
void printPreviewShare() {
    printHeader(u8"🔹 Video Preview & Share");
    std::cout << u8"وڊيو ٺهڻ کان پوءِ، توهان ان کي ڏسي سگهو ٿا، محفوظ ڪري سگهو ٿا، ۽ دوستن سان شيئر به ڪري سگهو ٿا – WhatsApp، Facebook يا YouTube تي.\n\n";
}
void printOutro() {
    printHeader(u8"🔹 Outro");
    std::cout << u8"AI Sindhi Video App –\n";
    std::cout << u8"توهان جي ٻولي، توهان جو مستقبل.\n";
    std::cout << u8"هاڻي سنڌيءَ ۾ سکڻ، پڙهڻ ۽ وڊيو ٺاهڻ بلڪل آسان!\n\n";
}
int main() {
    // Ensure locale/terminal supports UTF-8 for correct Sindhi display.
    // On many systems this is fine if terminal encoding is UTF-8.
    printIntro();
    printHomeScreen();
    printEducationMode();
    printPoetryStories();
    printPreviewShare();
    printOutro();
    return 0;
}

<!--
**mohsinbaladi/mohsinbaladi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# 📝 Intelli Notes (formerly My Notes App)
A sleek and intuitive note-taking application created using Flutter and Firebase, now enhanced with AI features powered by Google Gemini and fortified with robust encryption!

## ✨ Enhanced Features
- 🔐 Secure user authentication using Firebase Auth
- 💾 Efficient storage and retrieval of notes using Firebase Firestore
- 🔒 End-to-end encryption for all note content
- 🌙 Stylish dark mode interface with smooth toggle
- 🔗 Dedicated section for optional links in each note
- 🎨 Improved UI with color-coded notes and card layouts
- 🔍 Advanced search functionality to easily find notes
- 🧠 AI-powered title generator for your notes
- 💬 Chat with your notes using AI assistance
- 🏷️ Tag system for better note organization
- 📌 Pin important notes to the top
- 🗂️ Archive functionality for better note management
- 🗑️ Trash system with auto-deletion after 30 days
- 📊 Staggered grid view for dynamic note display
- 🖌️ Color filter for easy note browsing
- 📱 Responsive design for various screen sizes
- 🔑 Reset PIN feature for locked notes
- 🔄 Automatic app update checks using Firebase Remote Config
- ⏰ Reminder system for both standalone reminders and note-specific reminders
- 📅 Calendar view for managing reminders
- 🔔 Local notifications for reminders
- 🗓️ Ability to set date and time for reminders
- 🔄 Sync reminders across devices using Firebase
- 🎨 Customizable app theme with color selection
- 🖋️ Adjustable font size and family
- ⚙️ Comprehensive settings screen for app customization
- 🔏 Beautiful and informative Privacy Policy screen
- 🎭 Animated text effects for engaging user experience
- 🗂️ Expandable sections for better information organization
- 🎨 Theme-aware UI elements for consistent look and feel
- 🎙️ Voice-to-text functionality for easy note creation
- 🧠 AI-powered conversion of voice notes to structured text
- 🌚 AMOLED black theme for OLED screens
- 📷 Image-to-text functionality using Google ML Kit
- ✅ Todo list management with AI-powered generation

## 🔐 Security Features
- **End-to-End Encryption**: All note content is encrypted using AES encryption before being stored in the database
- **Locked Notes**: Secure your sensitive notes with a 4-digit PIN
- **PIN Reset**: Easily reset your PIN if forgotten, with email verification for added security
- **Auto-lock**: Locked notes are automatically hidden from the main view
- **Secure Storage**: Encrypted notes are stored in Firebase Firestore, ensuring data remains protected even if the database is compromised

## 📋 Todo List Management
- Create, edit, and delete todo items
- Mark todos as completed with a checkbox
- Set reminders for individual todo items
- Search functionality to quickly find specific todos
- Swipe-to-delete for easy todo removal
- Long-press to edit or delete todos
- AI-powered todo list generation from context
- Prioritized todo list with time estimates (AI-generated)
- Local notifications for todo reminders

## 🔄 App Updates
- Now you can check for updates using Firebase Remote Config
- Seamless update process with in-app prompts
- Ensures users always have the latest features and security improvements
- You can get the latest version from the GitHub repository

## 🔒 Privacy Policy Screen
- Sleek and modern design with card-based layout
- Animated title for engaging user experience
- Expandable sections for easy navigation through policy details
- Dark mode support for comfortable reading in any lighting condition
- Clear presentation of data collection, usage, and security practices
- Easy-to-find contact information for user inquiries

## 🤖 AI Features
- **AI Title Generator**: Automatically generate catchy and relevant titles for your notes using Google Gemini AI
- **Chat with Notes**: Engage in a conversation about your notes with an AI assistant, powered by Google Gemini
- **AI-Powered Note Manipulation**: Use special commands to modify your notes with AI assistance
- **Voice-to-Text Conversion**: Convert spoken words into text notes with AI-powered enhancement

### AI Commands
Our app includes powerful AI-driven commands to help you manipulate and enhance your notes:

- **/edit**: Allows you to make specific edits to your note content using natural language instructions.
- **/update**: Similar to /edit, but typically used for broader updates or additions to your note.
- **/rewrite**: Completely rewrites your note while maintaining the core message, useful for improving clarity or changing the tone.
- **/addemoji**: Enhances your note by adding relevant emojis to key points or sections.
- **/translate**: Translates your note content into a specified language.

## 🌈 Color Coding
- Easily categorize and visually organize your notes with a selection of colors
- Choose from a range of preset colors when creating or editing a note
- Quickly identify note categories at a glance in the main notes list
- Filter notes by color for efficient organization

## 📋 Note Management
- **Archive**: Move less frequently used notes to the archive for a cleaner main view
- **Trash**: Safely delete notes with the ability to restore them within 30 days
- **Auto-deletion**: Notes in the trash are automatically deleted after 30 days

## ⏰ Reminder System
- Create standalone reminders or attach reminders to specific notes
- View reminders in a calendar interface
- Set custom date and time for each reminder
- Receive local notifications for reminders
- Edit and delete reminders easily
- Sync reminders across devices using Firebase
- Automatic deletion of expired reminders

## 🎨 Theme Customization
- Toggle between light and dark modes
- Choose from a variety of theme colors
- Adjust font size for better readability
- Select preferred font family
- Preview theme changes in real-time

## 🎙️ Speech-to-Note Feature
- Convert spoken words into text notes using advanced speech recognition
- Real-time transcription with visual feedback
- AI-powered enhancement of transcribed text into well-structured notes
- Intuitive interface with a floating action button for easy recording
- Clear visualization of recording status with animated microphone icon
- Options to clear, re-record, or convert the transcribed text

## 📷 Image-to-Text Feature
- Extract text from images using Google ML Kit
- Support for both camera capture and gallery image selection
- Automatically append extracted text to your note content
- User-friendly interface for seamless integration with note-taking workflow

## ⚙️ Settings Screen
- Access all app customization options in one place
- Easily toggle dark mode
- Select theme color from a dropdown menu
- Adjust font size using a slider
- Choose font family from available options
- Preview text changes in real-time

## 📸 Screenshots
![Main image](https://github.com/user-attachments/assets/f445b58c-2fb3-4cd2-81bf-fa076af234c2)

## 🛠️ Technologies Used
- 📱 Flutter for cross-platform development
- 🔑 Firebase Authentication for secure user management
- 🗄️ Firebase Firestore for real-time data storage
- 🔄 Firebase Remote Config for dynamic app updates
- 🤖 Google Gemini for AI-powered features
- 🔒 AES encryption for robust data protection
- 📊 flutter_staggered_grid_view for dynamic note layouts
- 🎭 animated_text_kit for engaging text animations
- 🔗 url_launcher for opening links within notes
- 📤 share_plus for sharing note content
- 💾 shared_preferences for local data storage
- 🎨 flutter_colorpicker for color selection
- 📅 table_calendar for calendar view
- 🔔 flutter_local_notifications for local reminders
- 🔄 firebase_messaging for cross-device sync of reminders
- 🎨 Provider package for state management and theme customization
- 🗣️ speech_to_text for voice recognition
- 💡 google_generative_ai for AI-powered text enhancement
- ✨ avatar_glow for visual recording indicator
- 📷 image_picker for selecting images from gallery or camera
- 🖼️ google_mlkit_text_recognition for extracting text from images
- 📅 intl package for date formatting

## 🚀 Getting Started
1. 📥 Clone the repository
2. 📦 Install dependencies using `flutter pub get`
3. 🔧 Set up Firebase
   - Create a new Firebase project
   - Add your Flutter app to the Firebase project
   - Download and add the configuration files to the appropriate directory
   - Enable Authentication and Firestore in your Firebase console
   - Set up Remote Config for app updates
4. 🤖 Set up Google Gemini
   - Obtain an API key for Google Gemini
   - Add the API key to your `key.dart` file (ensure it's kept secure and not exposed in public repositories)
5. 🔒 Set up Encryption
   - Generate a secure encryption key and initialization vector
   - Store these securely (consider using Flutter's secure storage options)
6. Set up Speech-to-Text
   - Add the `speech_to_text` plugin to your `pubspec.yaml`
   - Ensure necessary permissions are set in `AndroidManifest.xml` and `Info.plist`
7. Configure Google Generative AI
   - Add the `google_generative_ai` plugin to your `pubspec.yaml`
   - Set up your API key for Google Generative AI
8. Configure local notifications
   - Add the flutter_local_notifications plugin to your pubspec.yaml
   - Initialize the plugin in your app
9. Set up Image-to-Text
   - Add the `image_picker` and `google_mlkit_text_recognition` plugins to your `pubspec.yaml`
   - Ensure camera and gallery permissions are set up correctly
10. ▶️ Run the app using `flutter run`

## 📖 Usage
- 👤 Register or login with a sleek, user-friendly interface
- ➕ Tap the floating action button to add a new note or todo
- ✏️ Fill in the title, content, and an optional link for your note
- 🧠 Use the AI title generator to create a title based on your note content
- 🎨 Select a color for your note to categorize it
- 🏷️ Add tags to your notes for easy filtering
- 📌 Pin important notes to keep them at the top of your list
- 💾 Tap 'Save Note' to store your encrypted note securely
- 🔍 Use the search functionality in the app bar to find specific notes or todos
- 💬 Chat with your notes to get AI-powered insights and answers
- 🤖 Use AI commands (/edit, /update, /rewrite, /addemoji, /translate) to manipulate your notes
- 🌓 Toggle between light and dark modes for comfortable viewing
- 🗂️ Archive notes you don't need frequently
- 🗑️ Move notes to trash and restore them if needed
- 🎨 Use color filters to browse notes by category
- 🔐 Set a PIN to lock sensitive notes
- 🔑 Reset your PIN if forgotten, using email verification
- 🔄 Receive prompts for app updates when available
- ⏰ Access the reminder screen from the main menu
- 📅 View your reminders in a calendar format
- ➕ Add new reminders by tapping the "Add Reminder" button
- 🖊️ Edit reminders by tapping on them in the list
- 🗑️ Delete reminders by swiping left on the reminder item
- 🔔 Receive notifications for your reminders at the set time
- 📎 Attach reminders to specific notes for better organization
- ⚙️ Access the Settings screen to customize app appearance
- 🎨 Choose your preferred theme color
- 🖋️ Adjust font size and family for better readability
- 🌓 Toggle dark mode easily from the Settings screen
- 🎙️ Access the voice note feature from the add screen
- 🗣️ Tap the microphone button to start recording your note
- 📝 Watch as your speech is transcribed in real-time
- 🧠 Use the AI-powered conversion to transform your voice note into a structured text note
- 💾 Save or edit the converted note as needed
- 📷 Use the image-to-text feature to extract text from images
- 📸 Capture an image or select from gallery to extract text
- 📝 Review and edit the extracted text before adding it to your note
- ✅ Create new todos by tapping the floating action button in the Todo List screen
- 📅 Set reminders for individual todos with date and time
- ✔️ Mark todos as completed by tapping the checkbox
- 🔍 Search for specific todos using the search bar
- 🖐️ Long-press on a todo to edit or delete it
- 👆 Swipe left on a todo to quickly delete it
- 🤖 Generate AI-powered todo lists by providing context or description of tasks
- 📊 View prioritized todo lists with time estimates (AI-generated)
- 🔔 Receive local notifications for todo reminders

## 🆕 UI Enhancements
- Color-coded notes for easy visual categorization
- Card-based layout for better organization
- Staggered grid view for dynamic note display
- Animated text effects for engaging user experience
- Responsive design for various screen sizes
- Customizable color filters for note browsing
- Drawer menu for easy navigation between notes, archive, and trash
- Calendar view for easy reminder management
- Sleek reminder creation and editing interface
- Comprehensive Settings screen for app customization
- Real-time theme preview in Settings
- Animated microphone button for clear recording status indication
- Bottom sheet interface for voice note recording and conversion
- Real-time transcription display in a scrollable container
- Image-to-text interface integrated seamlessly with note creation

## 🤝 Contributing
Contributions, issues, and feature requests are welcome. Feel free to check [issues page](https://github.com/Piyu-Pika/my_notes_app/issues) if you want to contribute.

## 👨‍💻 Author
Piyush Bhardwaj

## 🙏 Acknowledgements
- Flutter framework
- Firebase platform
- Google Gemini AI
- flutter_staggered_grid_view package
- animated_text_kit package
- url_launcher package
- share_plus package
- intl package for date formatting
- shared_preferences package
- flutter_colorpicker package
- encrypt package for AES encryption
- table_calendar package for the calendar view
- flutter_local_notifications package for local reminders
- firebase_messaging for cross-device reminder sync
- Provider package for state management
- speech_to_text package for voice recognition
- google_generative_ai package for AI-powered features
- avatar_glow package for visual feedback
- image_picker package for image selection

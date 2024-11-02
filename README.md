# 🎵 PulsePlay: Bringing Music to Life with Ruby on Rails 🎵

This project is a music-sharing platform, built with Ruby on Rails 7. Users can sign up, upload their music, and listen to tracks shared by other users using a sleek audio player.
![Uploading image.png…](https://github.com/iem-wahab/soundcloud/blob/main/Soundcloud%20snap%202.jpg?raw=true)
![Uploading image.png…](https://github.com/iem-wahab/soundcloud/blob/main/Soundcloud%20snap%201.jpg?raw=true)



## 🚀 Features
### User Authentication:
Powered by [Devise](https://github.com/heartcombo/devise), allowing users to sign up, log in, and manage their accounts securely.

### Music Upload and Playback:
Users can upload music files, which are then playable through a visually appealing waveform player powered by [wavesurfer.js](https://github.com/katspaugh/wavesurfer.js).

### Database:
PostgreSQL is used as the database to store user information and music tracks.

### Frontend Styling:
The project uses [Tailwind CSS](https://tailwindcss.com/) for a modern and responsive design. Sign-in and sign-up pages are styled using the [tailwind_devise gem](https://rubygems.org/gems/tailwind_devise).

## 🛠️ Installation and Setup
Prerequisites
Ruby 3.1+
Rails 7.x
PostgreSQL
Node.js and Yarn (for managing frontend dependencies)
Getting Started
1. Clone the repository:

 ```
git clone git@github.com:iem-wahab/soundcloud.git
cd soundcloud
 ```
2. Install dependencies:

## Install required Ruby gems and Node.js packages:

 ```
bundle install
yarn install
 ```
3. Setup the database:

Create and migrate the PostgreSQL database:

 ```
rails db:create
rails db:migrate
 ```
4. Run the server:

Start the Rails server locally:

 ```
rails server
 ```
Visit http://localhost:3000 in your browser to view the app.

## 🎧 Audio Player Integration
This project uses [wavesurfer.js](https://github.com/katspaugh/wavesurfer.js) for audio playback. The waveform player provides a great user experience by visualizing the sound waves of uploaded tracks. It is fully customizable and integrated seamlessly with Rails views.

## 💡 Usage
1. Users can sign up or log in using the authentication system powered by Devise.
2. After logging in, users can upload their music files (currently supporting MP3 format).
3. Other users can listen to uploaded tracks via the wavesurfer.js audio player.
4. Users can manage their profiles and see the music uploaded by others.

## 🎨 Styling

The frontend is styled with Tailwind CSS, a utility-first CSS framework that ensures a responsive and modern UI. Sign-in and sign-up forms are styled with the tailwind_devise gem for an out-of-the-box elegant design.

## 📦 Gems and Libraries

1. Rails 7 - Backend framework
2. Devise - User authentication
3. PostgreSQL - Database
4. Tailwind CSS - CSS framework
5. wavesurfer.js - JavaScript audio player
6. tailwind_devise - Styling for authentication pages

## 🌟 Future Enhancements

1. Add social features such as likes, comments, and followers.
2. Enable more file formats for uploads.
3. Implement background processing for handling large audio files.
4. Integrate search functionality to find users or music.
5. Add playlists and favorites for user engagement.

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

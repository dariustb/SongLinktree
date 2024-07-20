---
# Worked Up! release page as index

layout:    default
Title:     Worked Up!
permalink: /
---
<html lang="en">

<!-- Meta information to call here -->
<head>

    <!-- Metadata -->
    <meta charset="utf-8">
    <meta name="author" content="{{ site.author }}">
    <meta name="description" content="{{ site.description }}">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Page Title -->
    <title>Worked Up! - {{ site.title }}</title>

    <!-- CSS -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lora&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&display=swap" rel="stylesheet">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <link href="/assets/css/tailwind.css" rel="stylesheet">


    <!-- Favicons -->
    <!-- <link rel="shortcut icon" href="/assets/images/icons/bizkid.ico" />
    <link rel="apple-touch-icon" href="/assets/images/icons/bizkid.ico" /> -->

</head>

<body class="bg-sl-bgcolor text-sl-black text-center">

    <!-- Necessary loader and site header information -->

    <!-- Site content to use in each unique page -->

    <!-- Cover Hero Section -->
    <section>
    
        <div class="relative w-screen" style="height: 100vw;">

            <!-- Blurred banner Image -->
            <img class="object-cover w-full h-full blur-sm" 
                 src="assets/images/worked-up/WorkedUpCrop_709x1038.png" 
                 alt="Worked Up banner image" />

            <!-- Album Cover -->
            <div class="absolute top-0 left-0 m-8 drop-shadow-[0_0px_4px_rgba(0,0,0,0.25)]">
                <img class="object-cover w-auto" 
                     src="assets/images/worked-up/WorkedUpCover_3000x3000.png" 
                     alt="Worked Up album cover" />
            </div>
    
        </div>
    
    </section>

    <!-- Music Player Section -->
    <!-- TODO: Implement Player functionalities -->
    <section>
        <div class="my-1 w-full h-3 bg-sl-liteblue drop-shadow-[0_0px_4px_rgba(0,0,0,0.25)]"></div>
    </section>

    <!-- Song Info Section -->
    <section>
        <h1 class="text-6xl font-roboto font-bold mt-8">Worked Up!</h1>
        <h2 class="text-xl font-lora italic my-4">by <b>The Bizkid</b></h2>
    </section>
    
    <hr>

    <!-- Links Section -->
    <section class="font-roboto">
    
        <h2 class="text-xl font-bold italic mt-4"><b>Stream now:</b></h2>

        <!-- Spotify -->
        <a href="https://open.spotify.com/track/419WEVULjmEInAtYh4W1xY?si=47cd864d64c44607">
            <div class="rounded-full mx-8 my-8 h-8 bg-sl-black drop-shadow-[0_0px_4px_rgba(0,0,0,0.25)]" data-aos="fade-up">
                <h2 class="text-xl text-white font-bold italic flex items-center justify-center">Spotify</h2>
            </div>
        </a>

        <!-- Apple Music -->
        <a href="https://music.apple.com/us/album/worked-up-feat-nariah-taylor/1758385676?i=1758385677">
            <div class="rounded-full mx-8 my-8 h-8 bg-sl-black drop-shadow-[0_0px_4px_rgba(0,0,0,0.25)]" data-aos="fade-up">
                <h2 class="text-xl text-white font-bold italic flex items-center justify-center">Apple Music</h2>
            </div>
        </a>

        <!-- Tidal -->
        <a href="https://tidal.com/browse/album/376194217">
            <div class="rounded-full mx-8 my-8 h-8 bg-sl-black drop-shadow-[0_0px_4px_rgba(0,0,0,0.25)]" data-aos="fade-up">
                <h2 class="text-xl text-white font-bold italic flex items-center justify-center">Tidal</h2>
            </div>
        </a>

        <!-- Youtube -->
        <a href="https://youtu.be/vHVLcIrz9HQ?si=Il4voMD4NBXgRUut">
            <div class="rounded-full mx-8 my-8 h-8 bg-sl-black drop-shadow-[0_0px_4px_rgba(0,0,0,0.25)] data-aos="fade-up"">
                <h2 class="text-xl text-white font-bold italic flex items-center justify-center">Youtube</h2>
            </div>
        </a>

        <!-- Soundcloud -->
        <a href="https://soundcloud.com/thebizkid/worked-up?si=6d7de5dc912d4a48b75aba0f198fcbd0&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing">
            <div class="rounded-full mx-8 my-8 h-8 bg-sl-black drop-shadow-[0_0px_4px_rgba(0,0,0,0.25)] data-aos="fade-up"">
                <h2 class="text-xl text-white font-bold italic flex items-center justify-center">Soundcloud</h2>
            </div>
        </a>

        <!-- Bandcamp -->
        <a href="https://thebizkid.bandcamp.com/track/worked-up">
            <div class="rounded-full mx-8 my-8 h-8 bg-sl-black drop-shadow-[0_0px_4px_rgba(0,0,0,0.25)] data-aos="fade-up"">
                <h2 class="text-xl text-white font-bold italic flex items-center justify-center">Bandcamp</h2>
            </div>
        </a>
    
    </section>

    <!-- Footer  -->
    <section>

        <p class="text-lg font-lora text-sl-darkblue italic mb-4">Released July 19, 2024</p>

        <div class="bg-sl-darkblue h-px w-full"></div>

        <p class="text-sm font-roboto italic my-8">Page designed & developed <br> by Darius Brown. <a href="https://github.com/dariustb/SongLinktree" class="underline text-sl-darkblue">View GitHub Repo</a></p> 
    
    </section>

    <!-- Necessary script calls to make site work -->
    <script>
        AOS.init();
    </script>

</body>

</html>

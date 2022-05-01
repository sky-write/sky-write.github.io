---
layout: post
title:  "Watson Text-To-Speech Implemented"
date:   2022-03-18 14:01:53 +0000
---
*(Updated 2022-04-11 20:27:14 +0000: New audio files added for Happy New Year, Happy Mother's Day, Ramadan Kareem and Happy Diwali)*

Hi again!

We are excited to announce that we have implemented IBM's Watson Text-To-Speech into SkyWrite!

When you look up to view the messages in the sky, the text-to-speech audio is played. There is a toggle to turn this on and off.
This has been implemented by having the audio files bundled with the app, so there is no delay when the user wants to view the messages in their postcode. This is currently the most efficient way given how few audio files we have, but if there were more - we may consider on downloading the audio files at runtime.

We currently use the Lisa V3 voice to say the messages out loud, but we are considering on implementing different voices and languages, but this is an optional feature for if we have time to implement it.

If you are interested on using Watson Text-To-Speech yourself, read more here: <https://cloud.ibm.com/docs/text-to-speech?topic=text-to-speech-gettingStarted>

Listen to the audio files here:
<table>
    <tr>
        <th>Message</th>
        <th>Audio file</th>
    </tr>
    <tr>
        <td>Happy Birthday</td>
        <td>
            <audio controls>
                <source src="https://raw.githubusercontent.com/sky-write/sky-write.github.io/gh-pages/docs/assets/audio/happy-birthday.mp3" type="audio/mpeg">
                Your browser does not support playing audio.
            </audio>
        </td>
    </tr>
    <tr>
        <td>Merry Christmas</td>
        <td>
            <audio controls>
                <source src="https://raw.githubusercontent.com/sky-write/sky-write.github.io/gh-pages/docs/assets/audio/merry-christmas.mp3" type="audio/mpeg">
                Your browser does not support playing audio.
            </audio>
        </td>
    </tr>
    <tr>
        <td>Congratulations</td>
        <td>
            <audio controls>
                <source src="https://raw.githubusercontent.com/sky-write/sky-write.github.io/gh-pages/docs/assets/audio/congratulations.mp3" type="audio/mpeg">
                Your browser does not support playing audio.
            </audio>
        </td>
    </tr>
    <tr>
        <td>Good luck</td>
        <td>
            <audio controls>
                <source src="https://raw.githubusercontent.com/sky-write/sky-write.github.io/gh-pages/docs/assets/audio/good-luck.mp3" type="audio/mpeg">
                Your browser does not support playing audio.
            </audio>
        </td>
    </tr>
    <tr>
        <td>Get well soon</td>
        <td>
            <audio controls>
                <source src="https://raw.githubusercontent.com/sky-write/sky-write.github.io/gh-pages/docs/assets/audio/get-well-soon.mp3" type="audio/mpeg">
                Your browser does not support playing audio.
            </audio>
        </td>
    </tr>
    <tr>
        <td>Thank you</td>
        <td>
            <audio controls>
                <source src="https://raw.githubusercontent.com/sky-write/sky-write.github.io/gh-pages/docs/assets/audio/thank-you.mp3" type="audio/mpeg">
                Your browser does not support playing audio.
            </audio>
        </td>
    </tr>
    <tr>
        <td>Happy New Year</td>
        <td>
            <audio controls>
                <source src="https://raw.githubusercontent.com/sky-write/sky-write.github.io/gh-pages/docs/assets/audio/happy-new-year.mp3" type="audio/mpeg">
                Your browser does not support playing audio.
            </audio>
        </td>
    </tr>
    <tr>
        <td>Happy Mother's Day</td>
        <td>
            <audio controls>
                <source src="https://raw.githubusercontent.com/sky-write/sky-write.github.io/gh-pages/docs/assets/audio/happy-mothers-day.mp3" type="audio/mpeg">
                Your browser does not support playing audio.
            </audio>
        </td>
    </tr>
    <tr>
        <td>Ramadan Kareem</td>
        <td>
            <audio controls>
                <source src="https://raw.githubusercontent.com/sky-write/sky-write.github.io/gh-pages/docs/assets/audio/ramadan-kareem.mp3" type="audio/mpeg">
                Your browser does not support playing audio.
            </audio>
        </td>
    </tr>
    <tr>
        <td>Happy Diwali</td>
        <td>
            <audio controls>
                <source src="https://raw.githubusercontent.com/sky-write/sky-write.github.io/gh-pages/docs/assets/audio/happy-diwali.mp3" type="audio/mpeg">
                Your browser does not support playing audio.
            </audio>
        </td>
    </tr>
<table>
# Bandcamp Dig
This repository is dedicated to tracking issues and feature requests for the Bandcamp Dig project. There is no source code included in this repository—its sole purpose is to provide a structured place for users to report problems, suggest improvements, and discuss functionality.

## About Bandcamp Dig

**Bandcamp Dig** is a project designed to help users maintain a queue of songs they intend to listen to on Bandcamp. Since Bandcamp itself does not provide this functionality, Bandcamp Dig offers an integrated solution consisting of:

* *Firefox Extension*: Enhances the Bandcamp experience by allowing users to manage their queue, automatically add new releases, and track listening history.
* *API & Email Parsing*: Enables automatic addition of releases to the queue based on Bandcamp purchase emails.
* *Website (bandcampdig.dirkdirk.com)*: Allows users to log in, view their queue, and manage their listening history.
* *iOS App*: Provides a mobile-friendly way to listen through your queue and track listen counts.

### Features

- **Account Creation**: Sign up for a Bandcamp Dig account via either the iOS app or the Firefox extension/website.
- **Queue Management**:
    - View your queue on the website.
    - Add all releases for an artist or label via the Firefox extension.
    - Add all releases that a Bandcamp user (fan) has bought to your queue.
- **Email Integration**: Set up an email forwarder to direct all emails from `bandcamp.com` to `incoming@bandcampdig.dirkdirk.com`, which will extract new release announcements and add them to your queue.
- **Autoplay**:
    - Automatically play through your queue in Firefox—when a song finishes, the next track page on Bandcamp is loaded.
    - Listen through your queue using the iOS app.
- **Play Stats**:
    - Track listen counts via autoplay on the Bandcamp website (Firefox extension).
    - Sync listen counts across the iOS app.
- **Smart Playback**:
    - Only play tracks that haven't been heard.
    - Prioritize the most recently added tracks in the queue.

## Purpose of This Repository

This repository is intended solely for **issue tracking and feature requests** related to Bandcamp Dig. If you encounter a bug, have a suggestion, or need help, you can open an issue here.

## Submitting an Issue

When creating an issue, please follow these guidelines:

### 1. **Check for Duplicates**

Before submitting a new issue, search the existing issues to see if someone has already reported the same problem or feature request.

### 2. **Provide a Clear Title**

Use a concise and descriptive title that summarizes the issue.

### 3. **Describe the Problem or Feature Request**

Include as much detail as possible:

- **For bugs:**
    - Steps to reproduce the issue.
    - Expected behavior vs. actual behavior.
    - Any error messages (if applicable).
    - Browser and OS version (if reporting a Firefox extension issue).
    - iOS version (if reporting an issue with the iOS app).
- **For feature requests:**
    - A clear explanation of the proposed functionality.
    - How it would improve the experience.

### 4. **Include Screenshots (If Applicable)**

Visual examples can help clarify the issue.

### 5. **Specify the Affected Component**

- Firefox Extension
- iOS App
- Website
- Email Parsing

### 6. **Be Respectful and Constructive**

This is an open space for discussion, but please remain respectful and constructive when providing feedback.

## Contribution and Support

This repository is for tracking issues only. If you're interested in contributing to the project, please reach out via the appropriate channels on the website or via email.

For general inquiries, send me an email, bandcampdig@dirkdirk.com

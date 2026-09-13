# Pose Finder Pro

Build Imanimito, an AI-powered animation reference app.

The core idea is simple: an animator uploads a video reference, and Imanimito analyzes the video and automatically extracts the most useful/key poses as individual reference images, so the animator doesn't have to scrub through the entire video manually.

Start by building the MVP interface and complete user flow:

A clean landing page introducing Imanimito

Video upload with drag-and-drop

Video preview after upload

An "Analyze Video" button

An analysis/loading screen

A results page displaying extracted key poses in chronological order

Each pose should show its frame number and timestamp

Users can select, deselect, and remove poses

Users can generate a clean reference sheet from the selected poses

Users can download the reference sheet

A simple dashboard showing previous projects

Use a dark, professional animation-software aesthetic with subtle lime/green accents. Keep the UI clean and visual, avoiding the generic "AI SaaS" look.

For now, use mock/sample video analysis and sample extracted frames so the entire experience works without an AI backend.

However, structure the application so the mock analysis can later be replaced with a real video-processing/pose-detection backend.

The eventual processing pipeline should be:

Upload Video → Analyze Frames → Detect Movement → Identify Key Poses → Remove Redundant Frames → Return Reference Images → Create Reference Sheet

The main purpose of Imanimito is not to generate animation. It is to turn video footage into useful animation references.

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://animitoref.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/511636f0-73cf-4b0f-9c45-6f8ef32e6bc1).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```

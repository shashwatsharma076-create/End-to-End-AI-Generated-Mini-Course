# 📺 ASSET GENERATION GUIDE
## Step-by-Step to Complete Your Mini-Course

---

## Step 1: Generate Slides (5 minutes)

### In Gamma.ai
1. Go to **gamma.app** and sign in
2. Click **"Create with AI"** → **"Presentation"**
3. Copy content from `slides/gamma-slides.md`:
   - Title: "Prompt Engineering for Beginners"
   - 10 slides with content
4. Choose theme: **"Modern Dark"**
5. Click **"Generate"**
6. **Export:** Download as PDF OR share publicly and paste link below:

**Your Gamma Link:**
```
https://gamma.app/share/[your-link-here]
```

---

## Step 2: Generate Voiceover (15 minutes)

### In ElevenLabs
1. Go to **elevenlabs.io** and sign in
2. Go to **Text to Speech**
3. Copy script from `scripts/final-script.md`
4. Select voice: **Rachel** (21m00XiQhS05F1HzF3D)
5. Settings (from `course-config.json`):
   - Stability: 0.5
   - Similarity: 0.8
   - Style: 0.5
6. Click **"Generate"**
7. **Download:** Save as `voiceover.mp3`

**Your Voice File:**
```
[Attach: voiceover.mp3]
```

---

## Step 3: Produce Avatar Video (30 minutes)

### In HeyGen
1. Go to **heygen.com** and sign in
2. Go to **Studios** → **"New Video"**
3. Click **"Upload Audio"** → Upload your `voiceover.mp3`
4. Choose avatar: **"Instructor - Professional"**
5. Enable: ✅ Lip sync ✅ Gestures
6. Background: **"Modern Office"**
7. Click **"Generate"**
8. Wait for processing (5-10 min)
9. **Download:** Save as `final-video.mp4`

**Your Video File:**
```
[Attach: final-video.mp4]
```

---

## Step 4: Commit Assets

```bash
# After creating all files:
git add voiceover.mp3 final-video.mp4
git commit -m "Add: Generated voiceover and video assets"
git push origin main
```

---

## 📋 PROGRESS CHECKLIST

| Task | Tool | Time | Status |
|------|------|------|--------|
| Generate slides | Gamma | 5 min | ⬜ |
| Generate voice | ElevenLabs | 15 min | ⬜ |
| Produce video | HeyGen | 30 min | ⬜ |
| Commit to repo | Git | 2 min | ⬜ |

---

## 🎯 After Completion

Once all assets are generated, your repo will have:

- ✅ Slides (Gamma link or PDF)
- ✅ Voiceover (.mp3)
- ✅ Video (.mp4)
- ✅ Quiz (documentation)
- ✅ Instructor guide

This = **Complete End-to-End AI Mini-Course** ready for LMS upload!
---
layout: post
title: "How to Fix Text Colors Not Showing in Imagitor"
lang: en
translation_id: fix-text-colors
date: 2026-06-08 13:00:00 +0000
categories: [troubleshooting, android, faq]
excerpt: "Are you changing text colors in Imagitor but the text remains black or white? Learn how to fix this common Android system settings issue."
---

One of the most common questions we receive from our users is: *"I'm trying to change the color of my text in Imagitor, but it's not working! The text just stays plain white or black."*

If you are experiencing this, don't worry! There is nothing wrong with the app. This issue is almost always caused by specific **system-level display settings** on your Android device that force all text to appear in high contrast or use a strict style. 

Here is how you can easily fix this issue.

### The Culprits: System Display & Accessibility Settings
Android has several accessibility and display features designed to make text easier to read globally across the entire phone. Unfortunately, when these settings are enabled, they override Imagitor's custom text colors. 

To fix your colors, you need to check your phone settings for the following four options and **turn them off**:

#### 1. High Contrast Text (Accessibility Settings)
This is the most common reason colors fail to show. It forces text to have a strong black or white outline to ensure it stands out.
- Go to your phone's **Settings** > **Accessibility**.
- Look for **High contrast text** (sometimes under "Vision" or "Display & text size").
- Toggle it **OFF**.

#### 2. High Contrast Text (Display Settings)
On some devices, this setting is located in the display menu instead of accessibility.
- Go to **Settings** > **Display** (or Display & Brightness).
- Search for **High contrast text**.
- Toggle it **OFF**.

#### 3. System-Level Bold Font
Forcing a bold font globally can sometimes strip custom text rendering in apps.
- Go to **Settings** > **Display** > **Font size and style**.
- If the **Bold font** switch is turned on, toggle it **OFF**.

#### 4. Custom System Fonts
If you have applied a custom system-wide font theme (often downloaded from a manufacturer's theme store), it might not support the coloring methods Imagitor uses.
- Try switching your device's font back to the **Default** system font in your Display or Theme settings.

### Note for Chinese Mobile Brands (Xiaomi, Oppo, Vivo, Realme, etc.)
If you are using a device from manufacturers like Xiaomi, Redmi, Poco, Oppo, Vivo, or Realme, keep in mind that their settings menus are heavily customized. 

The options mentioned above might have slightly different names or be hidden under different menus. For example:
- **Accessibility** might be hidden under **Additional Settings** or **System Settings**.
- **High Contrast Text** might be called **High-contrast text**, **Text contrast**, or part of an **Accessibility Menu** app.
- **Font styles** are often managed through a dedicated **Themes** app rather than regular display settings.

If you can't find these exact settings, simply use the **Search bar** at the very top of your phone's Settings app and search for words like *"Contrast"*, *"Bold"*, or *"Font"*.

Once you've disabled these overrides, return to Imagitor. Your text colors will now work perfectly!

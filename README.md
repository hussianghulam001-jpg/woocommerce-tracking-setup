# WooCommerce Tracking Setup — GTM, GA4 & Meta Pixel

A complete walkthrough of setting up a WooCommerce store on WordPress and connecting it to a full tracking stack using Google Tag Manager, Google Analytics 4, and the Meta Pixel.

## Overview

This repo documents the end-to-end process of:
- Installing WordPress and WooCommerce
- Configuring Google Tag Manager (triggers, variables, tags)
- Connecting Google Analytics 4 and Meta Pixel
- Verifying tracking with Google's Tag Assistant

---

## 1. Installing WordPress

The starting point — a fresh WordPress dashboard, ready for setup.


<img width="550" height="263" alt="image" src="https://github.com/user-attachments/assets/151e1ac0-9440-4f65-9834-10d68f1fd5c3" />


## 2. Installing WooCommerce

Searching, installing, and running through WooCommerce's guided setup.


<img width="554" height="271" alt="image" src="https://github.com/user-attachments/assets/87919a23-d183-4c48-892c-b2c22ed6ddb9" />

## 3. Setting Up Tracking with Google Tag Manager

### Variables

<img width="559" height="284" alt="image" src="https://github.com/user-attachments/assets/4f68c98a-9e50-4bb9-86cf-e3f2f3881aa6" />


### Triggers
- Form Submission
- Form Submission 1
- Trigger - Add to Cart


<img width="562" height="239" alt="image" src="https://github.com/user-attachments/assets/f9ad1ace-36dc-464c-976e-c3de0c98efd2" />


### Tags
- Dental Form Submit (GA4 Event)
- Meta Pixel (All Pages)
- Meta Pixel Event (Custom HTML)
- second (Google Tag / Base Config)


<img width="573" height="270" alt="image" src="https://github.com/user-attachments/assets/c30c2d13-4d63-4a43-90e8-f11cb8689280" />


## 4. Connecting GA4 and Meta Pixel

Both platforms were linked through GTM so every trigger fires the correct tag toward the correct destination — GA4 for on-site behavior and funnel analysis, Meta Pixel for retargeting and conversions.

## 5. Verifying with Tag Assistant

Confirmed live hits for **Add to Cart** and **Page View** events on the store.

<img width="553" height="257" alt="image" src="https://github.com/user-attachments/assets/9189d58b-c9b2-4179-aa57-f6de33a5af74" />



---

## Tech Stack

- WordPress + WooCommerce
- Google Tag Manager
- Google Analytics 4
- Meta (Facebook) Pixel

## Author

**Ghulam Hussain**


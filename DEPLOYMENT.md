# GitHub + Vercel Deployment Guide

## 1. Create GitHub Repository

Recommended repository name:

`restokron-site`

Description:

`Official website for restoKRON (rKRON), a Base network merchant payment token concept for restaurants, hospitality and KRON ecosystem payments.`

## 2. Upload Files

Upload all files and folders to the repository root:

- index.html
- assets/
- README.md
- DEPLOYMENT.md
- vercel.json
- .gitignore

## 3. Connect to Vercel

Vercel project settings:

- Framework Preset: Other
- Build Command: leave empty
- Output Directory: leave empty
- Install Command: leave empty

## 4. Add Domain

Add:

- restokron.com
- www.restokron.com

Recommended primary domain:

`https://www.restokron.com/`

## 5. DNS Records

For root domain:

Type: A
Name: @
Value: 76.76.21.21

For www:

Type: CNAME
Name: www
Target: cname.vercel-dns.com

# TikTok

**Mode**: 🔐 Browser · **Domain**: `tiktok.com`

## Commands

| Command | Description |
|---------|-------------|
| `opencli tiktok profile` | Get user profile info |
| `opencli tiktok search` | Search videos |
| `opencli tiktok explore` | Trending videos from explore page |
| `opencli tiktok user` | Get recent videos from a user |
| `opencli tiktok following` | List accounts you follow |
| `opencli tiktok friends` | Friend suggestions |
| `opencli tiktok live` | Browse live streams |
| `opencli tiktok notifications` | Get notifications |

## Usage Examples

```bash
# View a user's profile
opencli tiktok profile --username tiktok

# Search videos
opencli tiktok search --query "cooking" --limit 10

# Trending explore videos
opencli tiktok explore --limit 20

# Browse live streams
opencli tiktok live --limit 10

# List who you follow
opencli tiktok following

# Friend suggestions
opencli tiktok friends --limit 10

# JSON output
opencli tiktok profile --username tiktok -f json
```

## Prerequisites

- Chrome running and **logged into** tiktok.com
- [Browser Bridge extension](/guide/browser-bridge) installed

# Instagram AI Content Generator

Automated content generation pipeline that creates viral Instagram posts using AI and trend analysis.

## 🚀 Features

- **Automated Content Creation**: Generates carousels, reels scripts, and single posts
- **Trend Analysis**: Scrapes Reddit for trending topics in specific niches
- **AI-Powered Writing**: Uses Claude Opus for high-quality content generation
- **Smart Scheduling**: Calculates optimal posting times
- **Hashtag Optimization**: Generates 30 targeted hashtags with varied competition levels
- **Database Storage**: Stores all content in Baserow for easy management

## 🛠️ Tech Stack

- **n8n** - Workflow automation platform
- **Claude 3 Opus** - AI content generation
- **Baserow** - Database for content management
- **Reddit API** - Trend sourcing
- **Node.js** - Runtime environment

## 📊 Workflow Architecture

![Workflow Diagram](workflow/workflow-diagram.png)

### Workflow Components:
1. **Schedule Trigger**: Runs 3x daily at optimal times
2. **Configuration**: Sets niche, audience, and brand voice
3. **Trend Scraper**: Fetches trending topics from Reddit
4. **AI Analyzer**: Identifies viral content opportunities
5. **Content Creator**: Generates full Instagram content
6. **Hashtag Generator**: Creates optimized hashtag sets
7. **Database**: Stores everything in Baserow

## 📈 Results

- **Content Generation Time**: ~2 minutes per post
- **Output**: 3 high-quality posts daily
- **Customization**: Fully adaptable to any niche

## 🔧 Setup Guide

### Prerequisites
- n8n (self-hosted or cloud)
- Claude API key
- Baserow account
- Reddit API access (optional)

### Installation

1. Clone this repository
2. Import `workflow.json` into n8n
3. Configure credentials:
   - Add Claude API key
   - Set up Baserow token
4. Customize configuration node for your niche
5. Test with manual trigger
6. Enable schedule trigger

[Detailed setup instructions](docs/setup-guide.md)

## 📝 Sample Output

<details>
<summary>View Sample Carousel Content</summary>

### Slide 1: Hook
**Title:** "The 5 'Stupid' Questions Every Gym Beginner Is Too Afraid to Ask"
**Text:** The top 5 nobody talks about (but EVERYONE thinks)...

[Full sample](docs/sample-outputs/carousel-example.md)
</details>

## 🎯 Use Cases

- Social media managers
- Content creators
- Digital marketing agencies
- Personal brands
- E-commerce businesses

## 📊 Performance Metrics

- ✅ 90+ posts generated
- ✅ 15+ hours saved weekly
- ✅ Consistent posting schedule maintained
- ✅ Engagement-optimized content

## 🔄 Future Enhancements

- [ ] DALL-E integration for image generation
- [ ] Direct Instagram posting via API
- [ ] Performance analytics feedback loop
- [ ] A/B testing capabilities
- [ ] Multi-platform support (TikTok, LinkedIn)

## 📄 License

MIT License - See LICENSE file for details

## 🤝 Connect

Created by [Your Name]
- LinkedIn: [Your LinkedIn]
- Portfolio: [Your Website]

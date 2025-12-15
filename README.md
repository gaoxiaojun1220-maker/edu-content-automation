# edu-content-automation  

This repository contains a starter n8n workflow and templates for automating educational content creation across Chinese platforms (WeChat official account, Douyin, Xiaohongshu) for vocational education topics like career planning and admissions.  

## Overview  

The automation pipeline fetches a content brief (topic and audience), uses an AI service to generate draft text and a video script, converts these drafts into standardized templates for articles and short videos, and then schedules posts to the selected platforms. The repository includes:  
- `workflow.json`: a starter n8n workflow defining nodes for content retrieval, AI generation, template conversion, and scheduling posts.  
- `templates/video_script_template.md`: a simple template for short video scripts.  
- `templates/article_outline_template.md`: a template for WeChat article outlines.  
- `README.md`: this file.  

## Usage  

1. Import `workflow.json` into your self-hosted n8n instance.  
2. Update environment variables / credentials for the AI service and platform APIs (WeChat, Douyin, Xiaohongshu).  
3. Modify templates under the `templates` directory to match your brand voice and format.  
4. Trigger the workflow with a content brief to generate and schedule posts automatically.

# Incremental Load using Watermarking

## Strategy:
- Use `LastModified` column
- Store latest watermark value
- Query only rows where `LastModified > previousWatermark`
- Update watermark after each successful load
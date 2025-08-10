# docs4ai

**Status**: Active  
**Started**: August 9, 2025  
**GitHub**: https://github.com/Hits64/docs4ai  
**Type**: Open Source Tool

## Overview

Documentation crawler and search system built for AI workflows. Enables developers to maintain local copies of technical documentation for use with LLMs and AI assistants.

## Problem Solved

- AI assistants often lack access to up-to-date documentation
- Online docs can be slow or unavailable
- Need for structured, searchable local documentation
- Challenge of keeping multiple library docs organized

## Technical Stack

- **Language**: Python 3.x
- **Core Library**: crawl4ai (web scraping)
- **Architecture**: Modular (crawler, indexer, search, utils)
- **Storage**: Markdown files + JSON indexes
- **Interface**: CLI with argparse

## Key Features

1. **Auto-discovery**: Finds official docs URLs automatically
2. **Fast crawling**: 75+ pages/minute with concurrent processing
3. **Smart indexing**: Keyword extraction and categorization
4. **Powerful search**: Multiple search methods (keyword, category, library-specific)
5. **Minimal storage**: Efficient markdown + JSON structure

## Progress Timeline

### August 9, 2025
- Initial development and architecture design
- Implemented core modules (crawler, indexer, search)
- Created unified CLI interface
- Published to GitHub with comprehensive documentation
- Tested with 4 libraries (Pydantic, FastAPI, GitHub, Crawl4AI)

## Metrics

- **Crawling speed**: 75+ pages/minute
- **Search performance**: <100ms for keywords
- **Storage efficiency**: 95% reduction in metadata overhead
- **Initial libraries**: 4 pre-tested examples

## Future Ideas

- [ ] GUI interface for non-technical users
- [ ] Plugin system for custom extractors
- [ ] Integration with popular IDEs
- [ ] Automatic documentation updates via cron
- [ ] Support for more documentation formats
- [ ] Docker container for easy deployment

## Lessons Learned

1. **Clear positioning matters**: Changed from "AI-powered" to "Built for AI workflows"
2. **Clean repos attract contributors**: No pre-crawled content in repository
3. **Documentation-first approach**: Comprehensive README drives adoption
4. **Modular design pays off**: Easy to extend and maintain

## Resources

- [GitHub Repository](https://github.com/Hits64/docs4ai)
- [Main README](https://github.com/Hits64/docs4ai/blob/main/README.md)
- [Technical Details](https://github.com/Hits64/docs4ai/blob/main/CLAUDE.md)
# Update Log

## 2025-07-14: v1.1.2 - Bug Fix

### Fixed

- Fixed TypeError in `fromANDREWROBERTSList` function when processing CSV data with missing author information
- Added null check for authors field before calling split() method
- Improved error handling for data from Andrew Roberts' spreadsheet

## 2025-05-04: v1.1.0 - Major UI/UX Enhancement

### Added

- Responsive design for better mobile experience
- Modern UI with Google Material Design inspired styling
- Loading spinner for better feedback during searches
- Error handling with user-friendly error messages
- Accessibility improvements (ARIA labels, semantic HTML)
- Meta tags for better SEO and device compatibility

### Changed

- Updated PapaParse library to version 5.3.2
- Improved form layout with flexbox
- Enhanced search input field styling
- Better checkbox group organization
- Modernized button styling with hover effects
- Async/await implementation for better error handling
- Added proper HTML document language attribute

### Technical Improvements

- CSS custom properties (variables) for consistent theming
- Mobile-first responsive design
- Improved error handling for API calls
- Better loading state management
- Enhanced accessibility for screen readers
- Proper semantic HTML structure
- Optimized CSS with modern best practices

### Previous Updates

- 2022-02-01: v1.0.2 - Updated sheet name reference
- 2020-05-26: v1.0.1 - Added duplicate checker
- 2020-03-12: v1.0.0 - Initial release

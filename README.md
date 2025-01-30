# Flutter Product Listing Application Assignment

## Overview
Create a product listing application using Flutter and the BLoC pattern. This project will demonstrate your understanding of state management, UI design, Flutter, and Python backend (if you're up for the challenge).

## Requirements

### Technical Stack
- Flutter (latest stable version)
- BLoC pattern for state management
- Git for version control

### Core Features
1. **Product Listing**
   - Display a grid/list of products with basic information
   - You can find the sample data in this repo in [data.json](/data.json)
   - Each product card should show:
     - Product image
     - Name
     - Price
     - Rating
     - Brief description

2. **BLoC Implementation**
   - Create a ProductBloc to manage product-related states
   - Implement proper event handling
   - Handle loading, error, and success states
   - Use proper BLoC architecture with Events and States

3. **Search & Filtering**
   - Implement a search bar to filter products by name
   - Add category filters
   - Add price range filters
   - Implement sort functionality (price, rating)

4. **UI/UX**
   - Create a responsive layout that works on both phone and tablet
   - Implement smooth animations for loading states
   - Add pull-to-refresh functionality
   - Include proper error handling UI
   - Implement skeleton loading screens

### Bonus Features (Optional)
- Add product details page with transitions
- Implement pagination/infinite scroll
- Add dark mode support

## Project Structure

This is the sample structure for reference you don't have to follow the exact project structure:

```
lib/
├── blocs/
│   ├── product/
│   │   ├── product_bloc.dart
│   │   ├── product_event.dart
│   │   └── product_state.dart
│   └── filter/
│       ├── filter_bloc.dart
│       ├── filter_event.dart
│       └── filter_state.dart
├── models/
│   └── product.dart
├── repositories/
│   └── product_repository.dart
├── screens/
│   ├── home_screen.dart
│   └── product_detail_screen.dart
├── widgets/
│   ├── product_card.dart
│   ├── search_bar.dart
│   └── filter_bottom_sheet.dart
└── main.dart
```

## UI Design Guidelines
- Browse Figma Community for e-commerce/product listing inspiration or come up with your own design

## Submission Requirements
1. Create a GitHub repository with a clear, descriptive name
2. Include a detailed README.md containing:
   - Project description
   - Screenshots and video demo of the application
   - Setup instructions
   - List of implemented features
   - Technical decisions and architecture explanation
   - References to used libraries and resources
3. Add screenshots/GIFs demonstrating:
   - Product listing view
   - Search and filter functionality
   - Any animations or transitions
   - Responsive layout on different screen sizes

## Evaluation Criteria
- Clean, well-structured code
- Proper implementation of BLoC pattern
- UI/UX design and responsiveness
- Code organization and documentation
- Git commit history and messages
- Error handling and edge cases
- Performance and optimization

## Timeline
- Suggested completion time: 1 week
- Regular commits showing progressive development
- If you're unable to complete the challenge, please share your progress, thought process, reasons for the delay, and whether additional time would allow you to finish it.


## Additional Resources
- [Flutter Documentation](https://flutter.dev/docs)
- [flutter_bloc Package](https://pub.dev/packages/flutter_bloc)
- [Figma Community](https://www.figma.com/community)
- [Flask Documentation](https://flask.palletsprojects.com/)
- [HTTP Package for Flutter](https://pub.dev/packages/http)
- [DIO Package for Flutter](https://pub.dev/packages/dio)
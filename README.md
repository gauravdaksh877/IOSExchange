# Crypto Portfolio & Exchange iOS App

A pixel-perfect implementation of a crypto portfolio and exchange app built with SwiftUI, featuring dark mode design, interactive components, and smooth animations.

## 🎯 Features

### Implemented Screens:
1. **Portfolio Dashboard** - Complete with portfolio value, interactive chart, crypto assets, and recent transactions
2. **Transactions Summary** - Large portfolio card with action buttons and detailed transaction history
3. **Exchange Screen** - Full swap functionality with currency selection, amount input, and exchange details
4. **Bottom Navigation** - Functional tab bar with proper highlighting

### Key Features:
- ✅ Dark mode optimized UI
- ✅ Pixel-perfect design matching Figma specifications
- ✅ Mock data implementation for all screens
- ✅ Interactive components and animations
- ✅ Component-based architecture
- ✅ MVVM pattern with ObservableObject
- ✅ Responsive design for modern iPhones

## 🛠 Technical Implementation

### Architecture:
- **SwiftUI** - Modern declarative UI framework
- **MVVM Pattern** - Clean separation of concerns
- **ObservableObject** - Reactive data binding
- **Component-based** - Reusable UI components

### Project Structure:
```
IOSExchange/
├── ContentView.swift          # Main app structure with TabView
├── Views/
│   ├── PortfolioView.swift    # Dashboard screen
│   ├── TransactionsSummaryView.swift # Transactions screen
│   └── ExchangeView.swift     # Exchange/Swap screen
├── Models/
│   └── Models.swift           # Data models and mock data
└── Components/
    ├── TransactionRow.swift   # Reusable transaction component
    ├── ActionButton.swift     # Circular action buttons
    └── ExchangeDetailRow.swift # Exchange detail rows
```

## 📱 Setup Instructions

### Prerequisites:
- Xcode 15.0 or later
- iOS 17.0 or later
- macOS 14.0 or later

### Installation Steps:

1. **Clone or Download the Project**
   ```bash
   git clone <your-repo-url>
   cd IOSExchange
   ```

2. **Open in Xcode**
   ```bash
   open IOSExchange.xcodeproj
   ```

3. **Replace Your ContentView.swift**
   - Replace the content of your existing `ContentView.swift` with the provided code
   - Add the additional Swift files (`PortfolioView.swift`, `TransactionsSummaryView.swift`, `ExchangeView.swift`, `Models.swift`)

4. **Build and Run**
   - Select your target device (iPhone 13 or later recommended)
   - Press `Cmd + R` or click the Run button
   - The app should launch with the portfolio dashboard as the first screen

### File Organization:

Create these files in your Xcode project:

1. **ContentView.swift** - Main app structure (replace existing)
2. **PortfolioView.swift** - Portfolio dashboard screen
3. **TransactionsSummaryView.swift** - Transactions summary screen  
4. **ExchangeView.swift** - Exchange/swap screen
5. **Models.swift** - Data models and mock data provider

## 🎨 Design Implementation

### Color Scheme:
- **Primary Background**: Black (`Color.black`)
- **Card Backgrounds**: Gray with opacity (`Color.gray.opacity(0.1)`)
- **Accent Colors**: Blue and Purple gradients
- **Text Colors**: White primary, Gray secondary
- **Success Color**: Green for positive changes
- **Warning Color**: Orange for neutral/sending actions

### Components:
- **Gradient Cards** - Portfolio value cards with blue-purple gradients
- **Transaction Rows** - Consistent transaction display components
- **Action Buttons** - Circular buttons with icons
- **Currency Selectors** - Dropdown-style currency selection
- **Detail Rows** - Consistent formatting for exchange details

## 📊 Mock Data

The app uses comprehensive mock data including:
- Portfolio values and changes
- Cryptocurrency prices and balances
- Transaction history with different types
- Exchange rates and fees
- Chart data points for visualization

## 🚀 Features Demonstrated

### Portfolio Dashboard:
- Portfolio value display with change indicators
- Time frame selector (1h, 8h, 1d, 1w, 1m, 6m, 1y)
- Mock chart visualization
- Crypto asset cards (Bitcoin, Ethereum)
- Recent transactions list

### Transactions Summary:
- Large portfolio value card with gradient background
- Action buttons (Send, Add, Receive)
- Detailed transaction history
- Clean typography and spacing

### Exchange Screen:
- Currency swap interface
- Amount input fields
- Balance display
- Exchange rate calculation
- Fee breakdown (Rate, Spread, Gas fee)
- Final receive amount calculation

### Navigation:
- Bottom tab bar with 4 sections
- Proper tab selection highlighting
- Smooth transitions between screens

## 📸 Screenshots

The app matches the provided Figma design with:
- Exact color schemes and gradients
- Proper spacing and typography
- Consistent iconography
- Smooth animations and transitions

## ⚡ Performance Optimizations

- Lazy loading for transaction lists
- Efficient state management
- Optimized image rendering
- Smooth scrolling performance

## 🧪 Testing

Tested on:
- iPhone 15 Pro Simulator
- iPhone 14 Simulator  
- iPhone 13 Simulator
- Various screen sizes and orientations

## 🔄 Future Enhancements

Potential improvements for production:
- Real API integration
- Core Data persistence
- Advanced chart animations
- Biometric authentication
- Push notifications
- Haptic feedback implementation
- Advanced error handling
- Unit and UI tests

## 🐛 Known Limitations

- Uses mock data only (no backend integration)
- Chart is simplified visualization
- Currency selection is UI-only
- No data persistence between app launches

## 📝 Code Quality

The codebase follows:
- Swift coding standards
- Clean architecture principles
- Consistent naming conventions
- Proper component separation
- Comprehensive commenting
- Reusable component design

## 👥 Submission

**Developer**: Gaurav Kumar 
**Email**: gauravdaksh877@gmail.com 
**Date**: 9/08/2025  
**Assignment**: iOS Developer Position - Crypto Portfolio App

---


Screen Recording of App Flow

https://youtube.com/shorts/u3MHkitbqmA?feature=share

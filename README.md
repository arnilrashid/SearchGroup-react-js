# Search Group Component

A modern, responsive search component built with React, Tailwind CSS, and shadcn/ui. Perfect for filtering and searching through groups, teams, or any collection of items.

## Features

- 🔍 **Advanced Search**: Clean search input with real-time filtering
- 🎛️ **Smart Filters**: Multi-select filters with visual indicators
- 📊 **Flexible Sorting**: Sort by relevance, date, or member count
- 🎨 **Modern Design**: Built with Tailwind CSS and shadcn/ui patterns
- 📱 **Responsive**: Works seamlessly on desktop and mobile
- ⚡ **Interactive**: Smooth hover effects and transitions
- ♿ **Accessible**: Proper focus states and keyboard navigation

## Installation

1. Make sure you have the required dependencies:

```bash
npm install react lucide-react
```

2. Ensure you have Tailwind CSS configured in your project:

```bash
npm install -D tailwindcss
```

3. Copy the `SearchGroup.tsx` component to your project.

## Usage

```jsx
import SearchGroup from './components/SearchGroup';

function App() {
  return (
    <div className="App">
      <SearchGroup />
    </div>
  );
}
```

## Customization

### Filter Options
Modify the `filterOptions` array to customize available filters:

```jsx
const filterOptions = [
  { id: 'location', label: 'Location', icon: MapPin },
  { id: 'category', label: 'Category', icon: Tag },
  { id: 'status', label: 'Status', icon: Activity },
];
```

### Sort Options
Update the `sortOptions` array to change sorting criteria:

```jsx
const sortOptions = [
  { value: 'relevance', label: 'Relevance' },
  { value: 'alphabetical', label: 'A-Z' },
  { value: 'rating', label: 'Highest Rated' },
];
```

### Styling
The component uses Tailwind CSS classes. Customize colors, spacing, and layout by modifying the className props.

## Props

Currently, the component is self-contained with internal state management. Future versions may include:

- `onSearch`: Callback for search queries
- `onFilterChange`: Callback for filter changes
- `onSortChange`: Callback for sort changes
- `initialFilters`: Default selected filters
- `placeholder`: Custom search placeholder text

## Dependencies

- React 16.8+ (for hooks)
- Tailwind CSS 3.0+
- Lucide React (for icons)

## Browser Support

- Modern browsers (Chrome 60+, Firefox 60+, Safari 12+, Edge 79+)
- Mobile browsers (iOS Safari 12+, Chrome Mobile 60+)

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

MIT License - feel free to use this component in your projects!

## Screenshots

The component includes:
- Clean search interface with filter and sort controls
- Dropdown filter panel with checkboxes
- Active filter chips with remove buttons
- Real-time search preview
- Responsive design for all screen sizes

---

**Built with ❤️ using React, Tailwind CSS, and shadcn/ui**

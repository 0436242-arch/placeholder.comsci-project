
<!DOCTYPE html>
<html>

<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>
<p><em>hello</em></p>

<form class="search-container" action="/search" method="GET" role="search">
  <input 
    type="search" 
    id="search-bar" 
    name="q" 
    placeholder="Search for something..." 
    aria-label="Search through site content"
    required
  >
  <button type="submit" class="search-button">
    <!-- SVG Magnifying Glass Icon -->
    <svg xmlns="http://w3.org" viewBox="0 0 24 24" width="20" height="20" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
      <circle cx="11" cy="11" r="8"></circle>
      <line x1="21" y1="21" x2="16.65" y2="16.65"></line>
    </svg>
  </button>
</form>

</body>
</html>

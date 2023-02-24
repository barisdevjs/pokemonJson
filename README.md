# pokemonJson


-- usage
```
  const [xx, setXX] = useState<any[]>([]);
  
  useEffect(() => {
    fetch('https://serve1.onrender.com/api/pokemons/2', {
      method: 'DELETE'
    })
    .then((response) => {
      if (!response.ok) {
        throw new Error('Network response was not ok');
      }
      console.log('Pokemon deleted successfully');
    })
    .catch((error) => {
      console.error('There was a problem deleting the pokemon:', error);
    });
  }, []);
```
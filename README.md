## Demo
[**Try It Live**](https://ismail-shortly.netlify.app/)

## Screenshots
![Desktop Screenshot](screenshots/screenshot-shortly-desktop.png)
![Mobile Screenshot](screenshots/screenshot-shortly-mobile.png)

## Features
- **Quick URL Shortening**: Generate short links instantly.
- **Custom Aliases**: Create custom short codes (if supported).
- **Click Tracking**: Basic analytics for link clicks (if implemented).
- **API Support**: Integrate with applications via API (if available).

## Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/ismail9700/Shortly.git
   ```
2. Navigate to the directory:
   ```bash
   cd Shortly
   ```
3. Install dependencies:
   ```bash
   npm install  # or pip install -r requirements.txt
   ```
4. Run the app:
   ```bash
   npm start  # or python app.py
   ```

## Usage
- Input a URL to shorten.
- Copy the generated short link.
- Track clicks (if supported).

Example:
```bash
curl -X POST http://localhost:3000/shorten -d '{"url": "https://example.com"}'
# Returns: http://short.ly/abcd123
```

## Contributing
1. Fork the repo.
2. Create a branch (`git checkout -b feature-branch`).
3. Commit changes (`git commit -m "Add feature"`).
4. Push (`git push origin feature-branch`).
5. Open a pull request.

## License
MIT License. See [LICENSE](LICENSE) for details.

## Contact
Reach out to [ismail9700](https://github.com/ismail9700) for inquiries.

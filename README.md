# create repo https://github.com/new → name: krishnan123, Public, Add README
git clone https://github.com/krishnan123/krishnan123.git
Copy-Item -LiteralPath "github-profile\README.md" -Destination "krishnan123\README.md" -Force
New-Item -ItemType Directory -Path "krishnan123\.github\workflows" -Force
Copy-Item -LiteralPath "github-profile\.github\workflows\snake.yml" -Destination "krishnan123\.github\workflows\snake.yml"
Set-Location krishnan123; git add .; git commit -m "feat: premium profile README"; git push


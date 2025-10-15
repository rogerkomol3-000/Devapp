<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Africa Store Santé Beauty</title>
    <link rel="icon" type="image/x-icon" href="/static/favicon.ico">
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <style>
        .admin-panel {
            display: none;
        }
        .admin-active .admin-panel {
            display: block;
        }
        .product-image {
            height: 200px;
            object-fit: cover;
        }
    </style>
</head>
<body class="bg-gray-100 font-sans">
    <!-- Header -->
    <header class="bg-green-800 text-white shadow-lg">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i data-feather="shopping-bag" class="w-8 h-8"></i>
                <h1 class="text-2xl font-bold">AfriBeauty Market</h1>
            </div>
            <div class="flex space-x-4">
                <button id="cartBtn" class="bg-yellow-500 hover:bg-yellow-600 text-white px-4 py-2 rounded-full flex items-center space-x-2 transition">
                    <i data-feather="shopping-cart"></i>
                    <span>Panier</span>
                </button>
                <button id="adminBtn" class="bg-red-500 hover:bg-red-600 text-white px-4 py-2 rounded-full flex items-center space-x-2 transition">
                    <i data-feather="lock"></i>
                </button>
            </div>
        </div>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-4 py-8">
        <!-- Category Navigation -->
        <nav class="mb-8 overflow-x-auto">
            <ul class="flex space-x-4">
                <li><button class="category-btn px-4 py-2 bg-green-700 text-white rounded-full" data-category="all">Tous</button></li>
                <li><button class="category-btn px-4 py-2 bg-green-600 text-white rounded-full" data-category="aliments">Compléments alimentaires</button></li>
                <li><button class="category-btn px-4 py-2 bg-green-500 text-white rounded-full" data-category="cosmetiques">Cosmétiques</button></li>
                <li><button class="category-btn px-4 py-2 bg-green-400 text-white rounded-full" data-category="beaute">Beauté</button></li>
                <li><button class="category-btn px-4 py-2 bg-green-300 text-white rounded-full" data-category="sante">Santé</button></li>
                <li><button class="category-btn px-4 py-2 bg-green-200 text-white rounded-full" data-category="bijoux">Bijoux</button></li>
            </ul>
        </nav>

        <!-- Products Grid -->
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6" id="productsContainer">
            <!-- Products will be dynamically loaded here -->
        </div>
    </main>

    <!-- Cart Modal -->
    <div id="cartModal" class="fixed inset-0 bg-black bg-opacity-50 z-50 hidden flex items-center justify-center">
        <div class="bg-white rounded-lg shadow-xl w-full max-w-md max-h-[80vh] overflow-y-auto">
            <div class="p-4 border-b flex justify-between items-center">
                <h2 class="text-xl font-bold">Votre Panier</h2>
                <button id="closeCart" class="text-gray-500 hover:text-gray-700">
                    <i data-feather="x"></i>
                </button>
            </div>
            <div class="p-4" id="cartItems">
                <!-- Cart items will be loaded here -->
                <p class="text-center text-gray-500 py-8">Votre panier est vide</p>
            </div>
            <div class="p-4 border-t">
                <div class="flex justify-between mb-4">
                    <span class="font-bold">Total:</span>
                    <span id="cartTotal" class="font-bold">0 FCFA</span>
                </div>
                <button id="checkoutBtn" class="w-full bg-green-600 hover:bg-green-700 text-white py-2 rounded-full flex items-center justify-center space-x-2 transition">
                    <span>Valider la commande</span>
                    <i data-feather="arrow-right"></i>
                </button>
            </div>
        </div>
    </div>

    <!-- Admin Login Modal -->
    <div id="adminLoginModal" class="fixed inset-0 bg-black bg-opacity-50 z-50 hidden flex items-center justify-center">
        <div class="bg-white rounded-lg shadow-xl w-full max-w-sm">
            <div class="p-4 border-b flex justify-between items-center">
                <h2 class="text-xl font-bold">Connexion Admin</h2>
                <button id="closeAdminLogin" class="text-gray-500 hover:text-gray-700">
                    <i data-feather="x"></i>
                </button>
            </div>
            <div class="p-4">
                <div class="mb-4">
                    <label class="block text-gray-700 mb-2" for="adminCode">Code d'accès:</label>
                    <input type="password" id="adminCode" class="w-full px-3 py-2 border rounded" placeholder="Entrez le code">
                </div>
                <button id="adminLoginBtn" class="w-full bg-red-600 hover:bg-red-700 text-white py-2 rounded-full transition">
                    Valider
                </button>
            </div>
        </div>
    </div>

    <!-- Admin Panel -->
    <div id="adminPanel" class="admin-panel fixed inset-0 bg-gray-800 bg-opacity-90 z-50 overflow-y-auto">
        <div class="container mx-auto px-4 py-8">
            <div class="flex justify-between items-center mb-8">
                <h2 class="text-2xl font-bold text-white">Panneau d'administration</h2>
                <button id="closeAdminPanel" class="text-white hover:text-red-300">
                    <i data-feather="x" class="w-8 h-8"></i>
                </button>
            </div>

            <div class="bg-white rounded-lg shadow-lg p-6 mb-8">
                <h3 class="text-xl font-bold mb-4">Configurer WhatsApp</h3>
                <div class="mb-4">
                    <label class="block text-gray-700 mb-2" for="whatsappNumber">Numéro WhatsApp:</label>
                    <input type="text" id="whatsappNumber" class="w-full px-3 py-2 border rounded" placeholder="Ex: +237692065919">
                </div>
                <button id="saveWhatsappBtn" class="bg-green-600 hover:bg-green-700 text-white px-4 py-2 rounded transition">
                    Enregistrer
                </button>
            </div>

            <div class="bg-white rounded-lg shadow-lg p-6">
                <h3 class="text-xl font-bold mb-4">Ajouter un produit</h3>
                <div class="mb-4">
                    <label class="block text-gray-700 mb-2" for="productName">Nom du produit:</label>
                    <input type="text" id="productName" class="w-full px-3 py-2 border rounded">
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700 mb-2" for="productCategory">Catégorie:</label>
                    <select id="productCategory" class="w-full px-3 py-2 border rounded">
                        <option value="aliments">Compléments alimentaires</option>
                        <option value="cosmetiques">Cosmétiques</option>
                        <option value="beaute">Beauté</option>
                        <option value="sante">Santé</option>
                        <option value="bijoux">Bijoux</option>
                    </select>
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700 mb-2" for="productPrice">Prix (FCFA):</label>
                    <input type="number" id="productPrice" class="w-full px-3 py-2 border rounded">
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700 mb-2" for="productDescription">Description:</label>
                    <textarea id="productDescription" class="w-full px-3 py-2 border rounded" rows="3"></textarea>
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700 mb-2">Image du produit:</label>
                    <div class="border-2 border-dashed border-gray-300 rounded-lg p-4 text-center">
                        <input type="file" id="productImage" class="hidden" accept="image/*">
                        <label for="productImage" class="cursor-pointer flex flex-col items-center">
                            <i data-feather="upload" class="w-8 h-8 text-gray-400 mb-2"></i>
                            <span class="text-gray-500">Cliquez pour importer une image</span>
                        </label>
                        <div id="imagePreview" class="mt-4 hidden">
                            <img id="previewImage" src="#" alt="Aperçu de l'image" class="max-h-40 mx-auto">
                        </div>
                    </div>
                </div>
                <button id="addProductBtn" class="w-full bg-blue-600 hover:bg-blue-700 text-white py-2 rounded-full transition">
                    Ajouter le produit
                </button>
            </div>

            <div class="bg-white rounded-lg shadow-lg p-6 mt-8">
                <h3 class="text-xl font-bold mb-4">Produits existants</h3>
                <div class="space-y-4" id="adminProductsList">
                    <!-- Products will be loaded here with delete button -->
                </div>
            </div>
        </div>
    </div>

    <script>
        // Initialize Feather Icons
        feather.replace();
        
        // Sample products data
        let products = [
            {
                id: 1,
                name: "Huile de Baobab",
                category: "cosmetiques",
                price: 5000,
                description: "Huile 100% naturelle pour la peau et les cheveux",
                image: "http://static.photos/nature/320x240/1"
            },
            {
                id: 2,
                name: "Moringa en poudre",
                category: "aliments",
                price: 3500,
                description: "Complément alimentaire riche en nutriments",
                image: "http://static.photos/food/320x240/2"
            },
            {
                id: 3,
                name: "Collier en perles",
                category: "bijoux",
                price: 8000,
                description: "Bijou traditionnel africain",
                image: "http://static.photos/vintage/320x240/3"
            }
        ];

        // Cart data
        let cart = [];
        
        // WhatsApp number
        let whatsappNumber = "+237692065919";
        
        // DOM elements
        const productsContainer = document.getElementById('productsContainer');
        const cartItemsContainer = document.getElementById('cartItems');
        const cartTotalElement = document.getElementById('cartTotal');
        const cartModal = document.getElementById('cartModal');
        const cartBtn = document.getElementById('cartBtn');
        const closeCart = document.getElementById('closeCart');
        const checkoutBtn = document.getElementById('checkoutBtn');
        const adminBtn = document.getElementById('adminBtn');
        const adminLoginModal = document.getElementById('adminLoginModal');
        const closeAdminLogin = document.getElementById('closeAdminLogin');
        const adminLoginBtn = document.getElementById('adminLoginBtn');
        const adminCodeInput = document.getElementById('adminCode');
        const adminPanel = document.getElementById('adminPanel');
        const closeAdminPanel = document.getElementById('closeAdminPanel');
        const whatsappNumberInput = document.getElementById('whatsappNumber');
        const saveWhatsappBtn = document.getElementById('saveWhatsappBtn');
        const addProductBtn = document.getElementById('addProductBtn');
        const productImageInput = document.getElementById('productImage');
        const imagePreview = document.getElementById('imagePreview');
        const previewImage = document.getElementById('previewImage');
        const adminProductsList = document.getElementById('adminProductsList');
        const categoryButtons = document.querySelectorAll('.category-btn');

        // Load products
        function loadProducts(category = 'all') {
            productsContainer.innerHTML = '';
            
            const filteredProducts = category === 'all' 
                ? products 
                : products.filter(product => product.category === category);
            
            if (filteredProducts.length === 0) {
                productsContainer.innerHTML = '<p class="col-span-full text-center text-gray-500 py-8">Aucun produit dans cette catégorie</p>';
                return;
            }
            
            filteredProducts.forEach(product => {
                const productCard = document.createElement('div');
                productCard.className = 'bg-white rounded-lg shadow-md overflow-hidden hover:shadow-lg transition';
                productCard.innerHTML = `
                    <div class="relative">
                        <img src="${product.image}" alt="${product.name}" class="w-full product-image">
                        <div class="absolute top-2 right-2 bg-green-600 text-white px-2 py-1 rounded-full text-xs">
                            ${getCategoryName(product.category)}
                        </div>
                    </div>
                    <div class="p-4">
                        <h3 class="text-lg font-bold mb-1">${product.name}</h3>
                        <p class="text-gray-600 text-sm mb-2">${product.description}</p>
                        <div class="flex justify-between items-center">
                            <span class="text-green-700 font-bold">${product.price.toLocaleString()} FCFA</span>
                            <button class="add-to-cart bg-green-600 hover:bg-green-700 text-white px-3 py-1 rounded-full text-sm transition" data-id="${product.id}">
                                Ajouter
                            </button>
                        </div>
                    </div>
                `;
                productsContainer.appendChild(productCard);
            });
            
            // Add event listeners to new "Add to cart" buttons
            document.querySelectorAll('.add-to-cart').forEach(button => {
                button.addEventListener('click', () => addToCart(parseInt(button.dataset.id)));
            });
        }

        // Get category name
        function getCategoryName(category) {
            const categories = {
                'aliments': 'Aliments',
                'cosmetiques': 'Cosmétiques',
                'beaute': 'Beauté',
                'sante': 'Santé',
                'bijoux': 'Bijoux'
            };
            return categories[category] || category;
        }

        // Add to cart
        function addToCart(productId) {
            const product = products.find(p => p.id === productId);
            if (!product) return;
            
            const existingItem = cart.find(item => item.id === productId);
            
            if (existingItem) {
                existingItem.quantity += 1;
            } else {
                cart.push({
                    id: product.id,
                    name: product.name,
                    price: product.price,
                    quantity: 1
                });
            }
            
            updateCart();
        }

        // Update cart
        function updateCart() {
            cartItemsContainer.innerHTML = '';
            
            if (cart.length === 0) {
                cartItemsContainer.innerHTML = '<p class="text-center text-gray-500 py-8">Votre panier est vide</p>';
                cartTotalElement.textContent = '0 FCFA';
                return;
            }
            
            let total = 0;
            
            cart.forEach(item => {
                total += item.price * item.quantity;
                
                const cartItem = document.createElement('div');
                cartItem.className = 'flex justify-between items-center py-2 border-b';
                cartItem.innerHTML = `
                    <div>
                        <h4 class="font-bold">${item.name}</h4>
                        <p class="text-sm text-gray-600">${item.price.toLocaleString()} FCFA x ${item.quantity}</p>
                    </div>
                    <div class="flex items-center space-x-2">
                        <span class="font-bold">${(item.price * item.quantity).toLocaleString()} FCFA</span>
                        <button class="remove-item text-red-500 hover:text-red-700" data-id="${item.id}">
                            <i data-feather="trash-2" class="w-4 h-4"></i>
                        </button>
                    </div>
                `;
                cartItemsContainer.appendChild(cartItem);
            });
            
            cartTotalElement.textContent = `${total.toLocaleString()} FCFA`;
            
            // Add event listeners to remove buttons
            document.querySelectorAll('.remove-item').forEach(button => {
                button.addEventListener('click', () => removeFromCart(parseInt(button.dataset.id)));
            });
            
            feather.replace();
        }

        // Remove from cart
        function removeFromCart(productId) {
            const itemIndex = cart.findIndex(item => item.id === productId);
            
            if (itemIndex !== -1) {
                if (cart[itemIndex].quantity > 1) {
                    cart[itemIndex].quantity -= 1;
                } else {
                    cart.splice(itemIndex, 1);
                }
            }
            
            updateCart();
        }

        // Checkout
        function checkout() {
            if (cart.length === 0) return;
            
            let message = "Bonjour, je souhaite commander les produits suivants:\n\n";
            
            cart.forEach(item => {
                message += `${item.name} - ${item.quantity} x ${item.price.toLocaleString()} FCFA\n`;
            });
            
            message += `\nTotal: ${cartTotalElement.textContent}\n\nMerci!`;
            
            const encodedMessage = encodeURIComponent(message);
            const whatsappUrl = `https://wa.me/${whatsappNumber.replace(/\D/g, '')}?text=${encodedMessage}`;
            
            window.open(whatsappUrl, '_blank');
        }

        // Admin login
        function adminLogin() {
            if (adminCodeInput.value === '001122') {
                adminLoginModal.classList.add('hidden');
                adminPanel.classList.remove('admin-panel');
                whatsappNumberInput.value = whatsappNumber;
                loadAdminProducts();
            } else {
                alert('Code incorrect');
            }
        }

        // Save WhatsApp number
        function saveWhatsappNumber() {
            whatsappNumber = whatsappNumberInput.value;
            alert('Numéro WhatsApp enregistré avec succès');
        }

        // Add product
        function addProduct() {
            const name = document.getElementById('productName').value.trim();
            const category = document.getElementById('productCategory').value;
            const price = parseInt(document.getElementById('productPrice').value);
            const description = document.getElementById('productDescription').value.trim();
            
            if (!name || !price || !description) {
                alert('Veuillez remplir tous les champs obligatoires');
                return;
            }
            
            // Generate a new ID (in a real app, this would be handled by a backend)
            const newId = products.length > 0 ? Math.max(...products.map(p => p.id)) + 1 : 1;
            
            const newProduct = {
                id: newId,
                name,
                category,
                price,
                description,
                image: previewImage.src || 'http://static.photos/minimal/320x240/4'
            };
            
            products.push(newProduct);
            
            // Clear form
            document.getElementById('productName').value = '';
            document.getElementById('productPrice').value = '';
            document.getElementById('productDescription').value = '';
            imagePreview.classList.add('hidden');
            productImageInput.value = '';
            
            // Reload products
            loadAdminProducts();
            loadProducts();
            
            alert('Produit ajouté avec succès');
        }

        // Load admin products
        function loadAdminProducts() {
            adminProductsList.innerHTML = '';
            
            if (products.length === 0) {
                adminProductsList.innerHTML = '<p class="text-center text-gray-500 py-8">Aucun produit</p>';
                return;
            }
            
            products.forEach(product => {
                const productItem = document.createElement('div');
                productItem.className = 'border rounded-lg p-4';
                productItem.innerHTML = `
                    <div class="flex justify-between items-start">
                        <div>
                            <h4 class="font-bold">${product.name}</h4>
                            <p class="text-sm text-gray-600">${getCategoryName(product.category)} - ${product.price.toLocaleString()} FCFA</p>
                            <p class="text-sm mt-1">${product.description}</p>
                        </div>
                        <button class="delete-product text-red-500 hover:text-red-700" data-id="${product.id}">
                            <i data-feather="trash-2" class="w-5 h-5"></i>
                        </button>
                    </div>
                `;
                adminProductsList.appendChild(productItem);
            });
            
            // Add event listeners to delete buttons
            document.querySelectorAll('.delete-product').forEach(button => {
                button.addEventListener('click', () => deleteProduct(parseInt(button.dataset.id)));
            });
            
            feather.replace();
        }

        // Delete product
        function deleteProduct(productId) {
            if (confirm('Voulez-vous vraiment supprimer ce produit?')) {
                products = products.filter(product => product.id !== productId);
                loadAdminProducts();
                loadProducts();
            }
        }

        // Event listeners
        document.addEventListener('DOMContentLoaded', () => {
            loadProducts();
            
            // Cart modal
            cartBtn.addEventListener('click', () => {
                cartModal.classList.remove('hidden');
            });
            
            closeCart.addEventListener('click', () => {
                cartModal.classList.add('hidden');
            });
            
            checkoutBtn.addEventListener('click', checkout);
            
            // Admin login
            adminBtn.addEventListener('click', () => {
                adminLoginModal.classList.remove('hidden');
            });
            
            closeAdminLogin.addEventListener('click', () => {
                adminLoginModal.classList.add('hidden');
            });
            
            adminLoginBtn.addEventListener('click', adminLogin);
            
            // Admin panel
            closeAdminPanel.addEventListener('click', () => {
                adminPanel.classList.add('admin-panel');
            });
            
            saveWhatsappBtn.addEventListener('click', saveWhatsappNumber);
            
            addProductBtn.addEventListener('click', addProduct);
            
            // Product image preview
            productImageInput.addEventListener('change', function() {
                if (this.files && this.files[0]) {
                    const reader = new FileReader();
                    
                    reader.onload = function(e) {
                        previewImage.src = e.target.result;
                        imagePreview.classList.remove('hidden');
                    }
                    
                    reader.readAsDataURL(this.files[0]);
                }
            });
            
            // Category filter
            categoryButtons.forEach(button => {
                button.addEventListener('click', () => {
                    loadProducts(button.dataset.category);
                });
            });
        });
    </script>
</body>
</html>
import React from "react";

const Home = () => {
  return (
    <div className="min-h-screen bg-gray-100 text-gray-900">
      {/* Header */}
      <header className="p-6 bg-yellow-700 text-white text-center text-2xl font-bold">
        Logo / Brand Name
      </header>

      {/* Hero Section */}
      <section className="p-10 text-center">
        <h1 className="text-4xl font-bold">Découvrez Nos Produits en Carton</h1>
        <p className="mt-4 text-lg">Éco-responsables, légers et durables</p>
      </section>

      {/* Product Gallery */}
      <section className="p-10 grid grid-cols-1 md:grid-cols-3 gap-6">
        <div className="bg-white shadow-md rounded-lg p-4">
          <img src="/placeholder.png" alt="Produit 1" className="w-full rounded-md" />
          <h2 className="mt-2 font-semibold">Produit 1</h2>
        </div>
        <div className="bg-white shadow-md rounded-lg p-4">
          <img src="/placeholder.png" alt="Produit 2" className="w-full rounded-md" />
          <h2 className="mt-2 font-semibold">Produit 2</h2>
        </div>
        <div className="bg-white shadow-md rounded-lg p-4">
          <img src="/placeholder.png" alt="Produit 3" className="w-full rounded-md" />
          <h2 className="mt-2 font-semibold">Produit 3</h2>
        </div>
      </section>

      {/* Contact Section */}
      <footer className="p-6 bg-yellow-700 text-white text-center">
        <h2 className="text-xl font-bold">Contactez-nous</h2>
        <p>Email: example@email.com</p>
        <p>Téléphone: +212 600 000 000</p>
        <p>Instagram: @yourbrand</p>
      </footer>
    </div>
  );
};

export default Home;

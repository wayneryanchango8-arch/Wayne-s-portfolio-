# Wayne-s-portfolio-
export default function Portfolio() { return ( <div className="min-h-screen bg-white text-gray-900"> {/* Hero Section */} <section className="max-w-5xl mx-auto px-6 py-20 text-center"> <h1 className="text-4xl font-bold mb-4">Wayne Ryan Change</h1> <p className="text-lg text-gray-600 mb-2">Freelance Software Engineer</p> <p className="text-xl font-medium mb-6"> Helping Hotels Increase Direct Bookings Through Better Websites </p> <a
href="https://wa.me/254705121766"
className="inline-block bg-black text-white px-6 py-3 rounded-2xl shadow"
> Request Free Website Audit </a> </section>

{/* About */}
  <section className="max-w-4xl mx-auto px-6 py-10">
    <h2 className="text-2xl font-semibold mb-4">What I Do</h2>
    <p className="text-gray-700 leading-relaxed">
      I help hotels and hospitality businesses improve their digital presence
      to increase direct bookings and reduce reliance on third-party platforms.
    </p>
    <ul className="mt-4 list-disc pl-6 text-gray-700 space-y-2">
      <li>Website redesign & upgrades</li>
      <li>Mobile performance optimization</li>
      <li>Direct booking systems</li>
      <li>SEO for international guests</li>
      <li>WhatsApp & inquiry integration</li>
    </ul>
  </section>

  {/* Problem Section */}
  <section className="bg-gray-50 py-10">
    <div className="max-w-4xl mx-auto px-6">
      <h2 className="text-2xl font-semibold mb-4">Why It Matters</h2>
      <p className="text-gray-700 mb-4">
        Most hotels lose bookings not because of demand, but because their website
        experience is slow or unclear.
      </p>
      <ul className="list-disc pl-6 text-gray-700 space-y-2">
        <li>Slow mobile performance reduces bookings</li>
        <li>Weak booking flow reduces conversions</li>
        <li>Poor SEO limits international visibility</li>
      </ul>
    </div>
  </section>

  {/* Pricing */}
  <section className="max-w-4xl mx-auto px-6 py-10">
    <h2 className="text-2xl font-semibold mb-6">Pricing</h2>
    <div className="space-y-4">
      <div className="border p-4 rounded-2xl">
        <h3 className="font-semibold">Website Upgrade</h3>
        <p className="text-gray-700">From $500 USD</p>
      </div>
      <div className="border p-4 rounded-2xl">
        <h3 className="font-semibold">New Website Build</h3>
        <p className="text-gray-700">From $750 USD</p>
      </div>
      <div className="border p-4 rounded-2xl">
        <h3 className="font-semibold">Growth Optimization</h3>
        <p className="text-gray-700">From $1,200 USD</p>
      </div>
    </div>
  </section>

  {/* CTA */}
  <section className="bg-black text-white py-16 text-center">
    <h2 className="text-2xl font-semibold mb-4">Get a Free Website Review</h2>
    <p className="mb-6">
      I can quickly review your hotel website and suggest improvements to increase bookings.
    </p>
    <a
      href="mailto:your@email.com"
      className="bg-white text-black px-6 py-3 rounded-2xl"
    >
      Contact Me
    </a>
  </section>

  {/* Footer */}
  <footer className="text-center py-6 text-gray-500 text-sm">
    Wayne Ryan Change • Freelance Software Engineer • +254705121766
  </footer>
</div>

); }

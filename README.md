import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";

export default function HomePage() {
  return (
    <div className="min-h-screen bg-white text-gray-800">
      {/* Header */}
      <header className="bg-red-600 text-white shadow sticky top-0 z-10">
        <div className="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
          <h1 className="text-2xl font-bold">রক্তবন্ধু | Thalassemia Help</h1>
          <nav className="space-x-4 hidden md:block">
            <a href="#about" className="hover:underline">থ্যালাসেমিয়া</a>
            <a href="#donor" className="hover:underline">রক্তদাতা</a>
            <a href="#patient" className="hover:underline">রোগী</a>
            <a href="#donate" className="hover:underline">সহায়তা</a>
            <a href="#blog" className="hover:underline">ব্লগ</a>
            <a href="#contact" className="hover:underline">যোগাযোগ</a>
          </nav>
        </div>
      </header>

      {/* Hero Section */}
      <section className="bg-red-100 py-16 text-center relative overflow-hidden">
  <img
    src="/images/hero-blood-donation.jpg"
    alt="থ্যালাসেমিয়া সচেতনতা হিরো ছবি"
    className="absolute inset-0 w-full h-full object-cover opacity-20"
  />
  <div className="relative z-10">
        <h2 className="text-4xl font-bold text-red-700 mb-4">থ্যালাসেমিয়া প্রতিরোধে সচেতন হোন</h2>
        <p className="text-lg mb-6">থ্যালাসেমিয়া একটি বংশগত রক্তরোগ, যা সচেতনতার মাধ্যমেই প্রতিরোধযোগ্য।</p>
        <div className="space-x-4">
          <Button className="bg-red-600 hover:bg-red-700 text-white">রক্ত দিন</Button>
          <Button variant="outline">যোগাযোগ করুন</Button>
          <Button variant="secondary">রোগী রেজিস্ট্রেশন</Button>
        </div>
      </div>
</section>

      {/* About Thalassemia */}
      <section id="about" className="py-12 px-4 max-w-5xl mx-auto">
  <img src="/images/thalassemia-awareness.jpg" alt="থ্যালাসেমিয়া সচেতনতা" className="w-full h-auto rounded-lg shadow mb-6" />
  <h3 className="text-2xl font-bold text-red-700 mb-4">থ্যালাসেমিয়া সম্পর্কে</h3>
  <div className="space-y-4 text-justify">
    <p><strong>থ্যালাসেমিয়া</strong> একটি জেনেটিক বা বংশগত রক্তরোগ যা হিমোগ্লোবিন উৎপাদনে বিঘ্ন ঘটায়। হিমোগ্লোবিন রক্তের একটি গুরুত্বপূর্ণ উপাদান যা দেহের কোষে অক্সিজেন পরিবহন করে। এই রোগে আক্রান্ত ব্যক্তিরা স্বাভাবিকভাবে রক্ত তৈরি করতে পারে না এবং তাদের জীবনে বারবার রক্ত গ্রহণের প্রয়োজন হয়। এটি ছোঁয়াচে নয়, কিন্তু বাবা-মার মাধ্যমে সন্তানের মধ্যে ছড়াতে পারে।</p>

    <p><strong>থ্যালাসেমিয়ার প্রকারভেদ:</strong> প্রধানত দুই ধরনের – আলফা ও বিটা থ্যালাসেমিয়া। আলফা থ্যালাসেমিয়ায় আলফা গ্লোবিন চেইন উৎপাদনে সমস্যা হয়, আর বিটা থ্যালাসেমিয়ায় বিটা গ্লোবিন চেইন উৎপাদন ব্যাহত হয়। এটি আবার মাইনর (বাহক) এবং মেজর (গুরুতর) রূপে বিভক্ত।</p>

    <p><strong>লক্ষণ ও উপসর্গ:</strong> অতিরিক্ত ক্লান্তি, ফ্যাকাশে ত্বক, হাড়ের গঠন পরিবর্তন, বৃদ্ধি বিলম্ব, enlarged spleen ইত্যাদি সাধারণ লক্ষণ।</p>

    <p><strong>রোগ নির্ণয়:</strong> CBC, Hemoglobin Electrophoresis, DNA Test, Ferritin Test, Prenatal Genetic Screening ইত্যাদির মাধ্যমে রোগ সনাক্ত করা হয়।</p>

    <p><strong>চিকিৎসা:</strong> নিয়মিত রক্তসঞ্চালন, Iron Chelation Therapy, Bone Marrow Transplant, এবং পুষ্টিকর খাদ্য গ্রহণের মাধ্যমে রোগ নিয়ন্ত্রণ করা যায়।</p>

    <p><strong>প্রতিরোধ:</strong> বিয়ের পূর্বে থ্যালাসেমিয়া স্ক্রিনিং, গর্ভাবস্থায় জিনগত পরীক্ষা, ও সচেতনতা বাড়ানোই এই রোগ প্রতিরোধের মূল উপায়।</p>

    <p><strong>সচেতনতা বার্তা:</strong> "একটি পরীক্ষা, একটি নিরাপদ ভবিষ্যৎ।"</p>

    <p><strong>তথ্য ও পরিসংখ্যান:</strong> বাংলাদেশে আনুমানিক ১০-১২% মানুষ থ্যালাসেমিয়ার বাহক এবং প্রতি বছর শত শত শিশু থ্যালাসেমিয়া নিয়ে জন্ম নেয়।</p>
  </div>
</section>

      {/* Become a Donor */}
      <section id="donor" className="py-12 bg-gray-50 px-4 max-w-5xl mx-auto">
  <img src="/images/blood-donation.jpg" alt="রক্তদান" className="w-full h-auto rounded-lg shadow mb-6" />
        <h3 className="text-2xl font-bold text-red-700 mb-4">রক্তদাতাদের জন্য</h3>
        <p className="mb-4">আপনি চাইলে রক্তদাতা হিসাবে নিবন্ধন করতে পারেন।</p>
        <Button>রক্তদাতা নিবন্ধন ফর্ম</Button>
      </section>

      {/* Patient Registration */}
      <section id="patient" className="py-12 px-4 max-w-5xl mx-auto">
  <img src="/images/patient-support.jpg" alt="রোগী সহায়তা" className="w-full h-auto rounded-lg shadow mb-6" />
        <h3 className="text-2xl font-bold text-red-700 mb-4">রোগীদের জন্য</h3>
        <p className="mb-4">রোগীর প্রোফাইল তৈরি করুন ও প্রয়োজনে রক্তের জন্য অনুরোধ করুন।</p>
        <Button variant="secondary">রোগীর তথ্য ফর্ম</Button>
      </section>

      {/* Donate or Support */}
      <section id="donate" className="py-12 bg-gray-50 px-4 max-w-5xl mx-auto">
  <img src="/images/donate-support.jpg" alt="সহায়তা করুন" className="w-full h-auto rounded-lg shadow mb-6" />
        <h3 className="text-2xl font-bold text-red-700 mb-4">ডোনেশন বা সাহায্য</h3>
        <p>আপনি বিকাশ, নগদ, বা ব্যাংকের মাধ্যমে সাহায্য পাঠাতে পারেন।</p>
        <ul className="list-disc pl-6 mt-4">
          <li>বিকাশ: 01XXXXXXXXX</li>
          <li>নগদ: 01XXXXXXXXX</li>
          <li>ব্যাংক: ABC ব্যাংক, অ্যাকাউন্ট: 1234567890</li>
        </ul>
      </section>

      {/* Blog or Awareness */}
      <section id="blog" className="py-12 px-4 max-w-5xl mx-auto">
  <img src="/images/blog-awareness.jpg" alt="সচেতনতা ব্লগ" className="w-full h-auto rounded-lg shadow mb-6" />
        <h3 className="text-2xl font-bold text-red-700 mb-4">সচেতনতামূলক ব্লগ</h3>
        <p className="mb-4">থ্যালাসেমিয়া বিষয়ে নিয়মিত পোস্ট ও আপডেট পাবেন এখানে।</p>
        <Button variant="outline">সব পোস্ট দেখুন</Button>
      </section>

      {/* Contact Section */}
      <section id="contact" className="py-12 bg-gray-100 px-4 max-w-5xl mx-auto">
  <img src="/images/contact-us.jpg" alt="যোগাযোগ" className="w-full h-auto rounded-lg shadow mb-6" />
        <h3 className="text-2xl font-bold text-red-700 mb-4">যোগাযোগ করুন</h3>
        <p>ঠিকানা: ১২৩/এ, স্বাস্থ্য রোড, ঢাকা<br />ফোন: ০১৭xxxxxxxxx<br />ইমেইল: info@rakto-bondhu.org</p>
        <Button className="mt-4">যোগাযোগ ফর্ম পূরণ করুন</Button>
      </section>

      {/* Footer */}
      <footer className="bg-red-600 text-white text-center py-6 mt-12">
        &copy; 2025 রক্তবন্ধু | Thalassemia Help. সর্বস্বত্ব সংরক্ষিত।
      </footer>
    </div>
  );
}

import ProfileSidebar from "@/components/ProfileSidebar";
import ProfileMain from "@/components/ProfileMain";

const Index = () => {
  return (
    <div className="min-h-screen bg-background">
      <div className="mx-auto max-w-[1280px] px-4 py-8 md:px-8">
        <div className="flex flex-col md:flex-row gap-8">
          <ProfileSidebar />
          <ProfileMain />
        </div>
      </div>
    </div>
  );
};

export default Index;

public class Chidalu extends Agbakwa {

    public String getSchool() {
        return "York University";
    }

    public String getDegree() {
        return "Software Engineering";
    }

    public String[] getFavoriteProgrammingLanguages() {
        return new String[]{"Java", "Python", "JavaScript (Node.js)"};
    }

    public String[] currentlyLearning() {
        return new String[]{"Angular", "SpringBoot"};
    }

    public String getCareerGoal() {
        return "Full-Stack Developer";
    }

    public String[] getWantToLearn() {
        return new String[]{"Microservice Architecture", "AWS",
                "Serverless / Full Stack Cloud"};
    }

    public Map<String, String> getSocialMediaHandles() {
        Map<String, String> socialHandles = Map.ofEntries(
                entry("Instagram", "A.Chidalu"),
                entry("Twitter", "@Chidalu4"),
                entry("LinkdenIn", "https://www.linkedin.com/in/a-chidalu/")
        );

        return socialHandles;
    }
}

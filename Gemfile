source "https://rubygems.org"   #has correct syntax
                                #should specify rubygems as a source using the SSL protocol on the first line

gem "sinatra", "1.4.4"          # should list the sinatra gem with the specific version 1.4.4
gem "hashie"                    #should list the hashie gem without specifying a version
gem "octokit", "~>2.0"          #should list the octokit gem specifying version 2.0 with a twiddle-wakka
gem "awesome_print", git: "git@github.com:awesome-print/awesome_print.git"   #should list the awesome_print gem specifying a remote git repository (use github)

                                 #groups
group :test do                   #should contain the pry gem in the development group using a hash argument to the gem method
end                              #should contain the rspec gem in the test group using block syntax
gem "rspec"
end

group :development do
gem "pry"
end

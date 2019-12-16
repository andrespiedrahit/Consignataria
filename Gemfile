$ cat << - EOT > /local/stacks/wordpress.gemfile
    joya "cc-wordpress",
        : git = & gt; "git: //github.com/cookbooks/cc-wordpress.git",
        : ref = & gt; 'eb0203133d14587e90f4'
        #: etiqueta = & gt; "0.10" o: branch = & gt; "qa", etc.
    gema "cc-mysql",: git = & gt; "git: //github.com/cookbooks/cc-mysql.git",
    gema "cc-apache2",: git = & gt; "git: //github.com/cookbooks/cc-apache2.git"
    gema "cc-php",: git = & gt; "git: //github.com/cookbooks/cc-php.git",
        : rama = & gt; "qa"
    gema "cc-openssl",: git = & gt; "git: //github.com/cookbooks/cc-openssl.git"
  EOT
    
$ bundle --gemfile /local/stacks/wordpress.gemfile \
         --install-path / local / chef-repo / cookbooks /

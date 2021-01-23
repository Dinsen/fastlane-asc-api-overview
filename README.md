
### Plugins

Dillinger is currently extended with the following plugins. Instructions on how to use them in your own application are linked below.

| Module | Implemented | Type | Endpoint |
| ------ | ------ | ------ | ------ |
| Tunes | X | PATCH | ageRatingDeclarations/#{age_rating_declaration_id} |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id}/ageRatingDeclaration |
| Tunes | X | PATCH | apps/#{app_id} |
| Tunes | X | GET | apps/#{app_id}/dataUsages |
| Tunes | X | GET | appPreviews/#{app_preview_id} |
| Tunes | X | POST | appPreviews |
| Tunes | X | PATCH | appPreviews/#{app_preview_id} |
| Tunes | X | DELETE | appPreviews/#{app_preview_id} |
| Tunes | X | GET | appPreviewSets |
| Tunes | X | GET | appPreviewSets/#{app_preview_set_id} |
| Tunes | X | POST | appPreviewSets |
| Tunes | X | PATCH | appPreviewSets/#{app_preview_set_id}/relationships/appPreviews |
| Tunes | X | GET | apps/#{app_id}/availableTerritories |
| Tunes | X | GET | appPrices |
| Tunes | X | GET | appPrices/#{app_price_id} |
| Tunes | X | GET | appPricePoints |
| Tunes | X | POST | appStoreReviewAttachments |
| Tunes | X | PATCH | appStoreReviewAttachments/#{app_store_review_attachment_id} |
| Tunes | X | DELETE | appStoreReviewAttachments/#{app_store_review_attachment_id} |
| Tunes | X | GET | appStoreVersionLocalizations/#{app_store_version_localization_id}/appScreenshotSets |
| Tunes | X | GET | appScreenshotSets/#{app_screenshot_set_id} |
| Tunes | X | POST | appScreenshotSets |
| Tunes | X | PATCH | appScreenshotSets/#{app_screenshot_set_id}/relationships/appScreenshots |
| Tunes | X | GET | appScreenshots/#{app_screenshot_id} |
| Tunes | X | POST | appScreenshots |
| Tunes | X | PATCH | appScreenshots/#{app_screenshot_id} |
| Tunes | X | DELETE | appScreenshots/#{app_screenshot_id} |
| Tunes | X | GET | apps/#{app_id}/appInfos |
| Tunes | X | PATCH | appInfos/#{app_info_id} |
| Tunes | X | PATCH | appInfos/#{app_info_id} |
| Tunes | X | DELETE | appInfos/#{app_info_id} |
| Tunes | X | GET | appInfos/#{app_info_id}/appInfoLocalizations |
| Tunes | X | POST | appInfoLocalizations |
| Tunes | X | PATCH | appInfoLocalizations/#{app_info_localization_id} |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id}/appStoreReviewDetail |
| Tunes | X | POST | appStoreReviewDetails |
| Tunes | X | PATCH | appStoreReviewDetails/#{app_store_review_detail_id} |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id}/appStoreVersionLocalizations |
| Tunes | X | POST | appStoreVersionLocalizations |
| Tunes | X | PATCH | appStoreVersionLocalizations/#{app_store_version_localization_id} |
| Tunes | X | DELETE | appStoreVersionLocalizations/#{app_store_version_localization_id} |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id}/appStoreVersionPhasedRelease |
| Tunes | X | POST | appStoreVersionPhasedReleases |
| Tunes | X | PATCH | appStoreVersionPhasedReleases/#{app_store_version_phased_release_id} |
| Tunes | X | DELETE | appStoreVersionPhasedReleases/#{app_store_version_phased_release_id} |
| Tunes | X | GET | apps/#{app_id}/appStoreVersions |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id} |
| Tunes | X | POST | appStoreVersions |
| Tunes | X | PATCH | appStoreVersions/#{app_store_version_id} |
| Tunes | X | PATCH | appStoreVersions/#{app_store_version_id} |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id}/resetRatingsRequest |
| Tunes | X | POST | resetRatingsRequests |
| Tunes | X | DELETE | resetRatingsRequests/#{reset_ratings_request_id} |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id}/appStoreVersionSubmission |
| Tunes | X | POST | appStoreVersionSubmissions |
| Tunes | X | DELETE | appStoreVersionSubmissions/#{app_store_version_submission_id} |
| Tunes | X | POST | appStoreVersionReleaseRequests |
| Tunes | X | GET | apps/#{app_id}/customAppUsers |
| Tunes | X | POST | customAppUsers |
| Tunes | X | DELETE | customAppUsers/#{custom_app_user_id} |
| Tunes | X | GET | apps/#{app_id}/customAppOrganizations |
| Tunes | X | POST | customAppOrganizations |
| Tunes | X | DELETE | customAppOrganizations/#{custom_app_organization_id} |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id}/idfaDeclaration |
| Tunes | X | POST | idfaDeclarations |
| Tunes | X | PATCH | idfaDeclarations/#{idfa_declaration_id} |
| Tunes | X | DELETE | idfaDeclarations/#{idfa_declaration_id} |
| Tunes | X | GET | sandboxTesters |
| Tunes | X | POST | sandboxTesters |
| Tunes | X | DELETE | sandboxTesters/#{sandbox_tester_id} |
| Tunes | X | GET | territories |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

<details><summary>AgeRatingDeclarations</summary>

| Module   | Added |   |
| -------- | ----- | - |
| Tunes    | ✅    |   |
| Tunes    | ✅    |   |
| Tunes    |       |   |
</details>

<details>
<summary>AppCategories</summary>

</details>

<details>
<summary>AppEncryptionDeclarations</summary>

</details>

<details>
<summary>AppInfoLocalizations</summary>

</details>

<details>
<summary>AppInfos</summary>

</details>

<details>
<summary>AppPreOrders</summary>

</details>

<details>
<summary>AppPreviewSets</summary>

</details>
<details>
<summary>AppPreviews</summary>

</details>
<details>
<summary>AppPricePoints</summary>

</details>
<details>
<summary>AppPriceTiers</summary>

</details>
<details>
<summary>AppPrices</summary>

</details>
<details>
<summary>AppScreenshotSets</summary>

</details>
<details>
<summary>AppScreenshots</summary>

</details>
<details>
<summary>AppStoreReviewAttachments</summary>

</details>
<details>
<summary>AppStoreReviewDetails</summary>

</details>
<details>
<summary>AppStoreVersionLocalizations</summary>

</details>
<details>
<summary>AppStoreVersionPhasedReleases</summary>

</details>
<details>
<summary>AppStoreVersionSubmissions</summary>

</details>
<details>
<summary>AppStoreVersions</summary>

</details>
<details>
<summary>Apps</summary>

</details>
<details>
<summary>BetaAppLocalizations</summary>

</details>
<details>
<summary>BetaAppReviewDetails</summary>

</details>
<details>
<summary>BetaAppReviewSubmissions</summary>

</details>
<details>
<summary>BetaBuildLocalizations</summary>

</details>
<details>
<summary>BetaGroups</summary>

</details>
<details>
<summary>BetaLicenseAgreements</summary>

</details>
<details>
<summary>BetaTesterInvitations</summary>

</details>
<details>
<summary>BetaTesters</summary>

</details>
<details>
<summary>BuildBetaDetails</summary>

</details>
<details>
<summary>BuildBetaNotifications</summary>

</details>
<details>
<summary>Builds</summary>

</details>
<details>
<summary>BundleIdCapabilities</summary>

</details>
<details>
<summary>BundleIds</summary>

</details>
<details>
<summary>Certificates</summary>

</details>
<details>
<summary>Devices</summary>

</details>
<details>
<summary>EndUserLicenseAgreements</summary>

</details>
<details>
<summary>FinanceReports</summary>

</details>
<details>
<summary>IdfaDeclarations</summary>

</details>
<details>
<summary>InAppPurchases</summary>

</details>
<details>
<summary>PreReleaseVersions</summary>

</details>
<details>
<summary>Profiles</summary>

</details>
<details>
<summary>RoutingAppCoverages</summary>

</details>
<details>
<summary>SalesReports</summary>

</details>
<details>
<summary>Territories</summary>

</details>
<details>
<summary>UserInvitations</summary>

</details>
<details>
<summary>Users</summary>

</details>
<details>
<summary>DiagnosticSignatures</summary>

</details>
<details>
<summary>GameCenterEnabledVersions</summary>

</details>


<details><summary>🚫 fastlane environment 🚫</summary>

### Stack

| Key                         | Value                                       |
| --------------------------- | ------------------------------------------- |
| OS                          | 11.0.1                                      |
| Ruby                        | 2.5.5                                       |
| Bundler?                    | false                                       |
| Git                         | git version 2.24.3 (Apple Git-128)          |
| Installation Source         | ~/.rbenv/versions/2.5.5/bin/fastlane        |
| Host                        | macOS 11.0.1 (20B50)                        |
| Ruby Lib Dir                | ~/.rbenv/versions/2.5.5/lib                 |
| OpenSSL Version             | OpenSSL 1.1.1d  10 Sep 2019                 |
| Is contained                | false                                       |
| Is homebrew                 | false                                       |
| Is installed via Fabric.app | false                                       |
| Xcode Path                  | /Applications/Xcode.app/Contents/Developer/ |
| Xcode Version               | 12.2                                        |


### System Locale

| Variable | Value       |   |
| -------- | ----------- | - |
| LANG     | en_US.UTF-8 | ✅ |
| LC_ALL   | en_US.UTF-8 | ✅ |
| LANGUAGE |             |   |


### fastlane files:

<details><summary>`./fastlane/Fastfile`</summary>

```ruby
require 'fileutils'
fastlane_require 'xcodeproj'

skip_docs # Do not create fastlane/README.txt

# Test and Validate

desc "Runs the unit tests and other verifications for the fastlane repo"
lane :test do |options|
  validate_repo
end

desc "Verifies all tests pass and the current state of the repo is valid"
lane :validate_repo do
  lint_source
  execute_tests
  validate_docs
  ensure_tool_name_formatting
  ensure_code_samples
  ensure_special_docs_code_samples
  ensure_code_snippets
  ensure_actions_config_items_formatting
end

desc "Verifies source code is in a good state"
lane :lint_source do
  # Verifying that no debug code is in the code base
  #
  exclude_dirs = ["\.bundle", "*/vendor/bundle"]
  ensure_no_debug_code(text: "binding.pry", extension: ".rb", exclude: "playground.rb", exclude_dirs: exclude_dirs) # debugging code
  ensure_no_debug_code(text: "# TODO", extension: ".rb", exclude_dirs: exclude_dirs) # TODOs
  ensure_no_debug_code(text: "now: ", extension: ".rb", exclude_dirs: exclude_dirs) # rspec focus
  ensure_no_debug_code(text: "<<<<<<<", extension: ".rb", exclude_dirs: exclude_dirs) # Merge conflict

  # spaceship and credentials_manager don't have access to fastlane_core
  ensure_no_debug_code(text: " UI\\.", path: "spaceship/lib", extension: ".rb", exclude_dirs: exclude_dirs)
  ensure_no_debug_code(text: " UI\\.", path: "credentials_manager/lib", extension: ".rb", exclude_dirs: exclude_dirs)

  rubocop(step_name: 'policekeeping_the_code_with_rubocop')

  Dir.chdir("..") do
    # Verify shell code style
    if FastlaneCore::Helper.mac?
      sh('find -E . -regex ".*\.(sh|bash)" -not -name "Pods-*" -name ".bundle" -exec shellcheck {} +')
    elsif !FastlaneCore::Helper.windows?
      sh('find . -regextype posix-egrep -regex ".*\.(sh|bash)" -not -name "Pods-*" -name ".bundle" -exec shellcheck {} +')
    end
  end
end

desc "Measure the execution time of the --help command"
lane :benchmark_help_command do
  Dir.chdir("..") do
    # install gnomon if not installed yet
    Actions.sh("echo foo | gnomon", log: true, error_callback: lambda { |result|
      if Helper.windows? || Helper.mac?
        sh('npm install -g gnomon')
      else
        sh('sudo npm install -g gnomon')
      end
    })
    cmd = Helper.windows? ? "cd bin && fastlane --help | gnomon" : "bin/fastlane --help | gnomon"
    3.times do
      content = sh(cmd, log: false)
      content.each_line do |line|
        UI.message("🏎️ '#{line.strip}'") if ["Total", "real", "user", "sys"].any? { |word| line.include?(word) }
      end
    end
  end
end

desc "Runs the tests"
lane :execute_tests do
  version = local_version # has to be outside of the `Dir.chdir`

  # Verifying the --help command
  Dir.chdir("..") do
    cmd = Helper.windows? ? "cd bin && fastlane --help" : "PAGER=cat bin/fastlane --help"
    content = sh(cmd)
    ["--version", "https://fastlane.tools", "fastlane"].each do |current|
      UI.user_error!("--help missing information: '#{current}'") unless content.include?(current)
    end
  end

  benchmark_help_command

  Dir.chdir("..") do
    # Install the bundle and the actual gem
    sh("bundle check || bundle install")
    sh("rake install")

    # Ensure the file size of the fastlane gem is below 1 MB
    size_in_mb = File.size("pkg/fastlane-#{version}.gem").to_f / (1024 * 1024)
    UI.user_error!("fastlane gem is above 1 MB, make sure no additional resources are included by mistake") if size_in_mb > 1

    # Run the tests
    sh("bundle exec rake test_all")
  end
end

# Release Management

desc "Increment the version number of this gem, after generating new Swift API"
lane :bump do |options|
  verify_env_variables
  ensure_git_branch(branch: "master")
  ensure_git_status_clean

  github_api_token = ENV["FL_GITHUB_RELEASE_API_TOKEN"]
  UI.user_error!("Please provide a GitHub API token using `FL_GITHUB_RELEASE_API_TOKEN`") if github_api_token.to_s.length == 0
  paths_for_commit = []

  version_file_path = "./fastlane/lib/fastlane/version.rb"

  # Verify everything is in a consistent state
  latest_version = current_version
  local_version = version_get_podspec(path: version_file_path, require_variable_prefix: false)
  UI.user_error!("Version on RubyGems doesn't match local repo: #{latest_version} != #{local_version}") if latest_version != local_version

  changelog_text = show_changelog

  bump_type ||= 'minor' if prompt(text: "New feature, method or API?", boolean: true)
  bump_type ||= 'patch'

  slug = "fastlane/fastlane"
  new_version = version_bump_podspec(path: version_file_path, bump_type: bump_type, require_variable_prefix: false)

  # Everything looks good, let's generate the Swift API
  generated_files = generate_swift_api(fastlane_version: new_version)

  # Alright, now let's update our FastlaneSwiftRunner manifest
  generated_files << generate_fastlane_swift_runner_manifest

  # Add all changed files to the version bump commit
  paths_for_commit += generated_files

  # Add version file path to change set
  paths_for_commit << version_file_path

  sh("bundle exec rake generate_team_table")
  paths_for_commit << "README.md"

  sh("bundle exec rake update_gem_spec_authors")
  paths_for_commit << "fastlane.gemspec"

  sh("git checkout -b 'version-bump-#{new_version}'")
  commit_message = "Version bump to #{new_version}"

  git_commit(path: paths_for_commit,
             message: commit_message)
  push_to_git_remote

  pr_body = ["Auto-generated by fastlane 🤖"]
  pr_body << "**Changes since release '#{latest_version}':**"
  pr_body << changelog_text
  pr_url = create_pull_request(
    api_token: github_api_token,
    repo: slug,
    title: commit_message,
    body: pr_body.join("\n\n")
  )

  if ENV['SLACK_URL']
    slack(
      channel: "action",
      default_payloads: [],
      message: "Version bump: #{pr_url} ✨",
      payload: {}
    )
  end

  # Revert to master branch
  sh("git checkout master")
end

desc "Generate the Swift api and test it"
lane :generate_swift_api do |options|
  Fastlane::VERSION = options[:fastlane_version] if options[:fastlane_version]

  require "../fastlane/lib/fastlane/swift_fastlane_api_generator.rb"
  swift_generator = Fastlane::SwiftFastlaneAPIGenerator.new
  generated_files = swift_generator.generate_swift
  Dir.chdir("swift/formatting") do
    sh("rake")
    UI.success("Done formatting fastlane.swift API")
  end
  UI.success("Done generating fastlane.swift API, ensuring it builds")
  gym(
    project: File.expand_path("swift/FastlaneSwiftRunner/FastlaneSwiftRunner.xcodeproj"),
    skip_package_ipa: true
  )
  sh("swift build")
  sh("rm -r ../.build")
  sh("rm ../FastlaneRunner")
  generated_files
end

desc "Generate the FastlaneSwiftRunner project manifest"
lane :generate_fastlane_swift_runner_manifest do |options|
  # Don't attempt to upgrade config files, like Fastfile.swift, Deliverfile.swift, etc...
  non_upgrade_set = TOOL_CONFIG_FILES.map { |tool_name| "#{tool_name}.swift" }.to_set

  swift_folder = File.expand_path("swift")
  runner_project_path = File.expand_path(File.join(swift_folder, "/FastlaneSwiftRunner/FastlaneSwiftRunner.xcodeproj"))
  project = Xcodeproj::Project.open(runner_project_path)

  swift_files = project.files
                       .reject { |file| file.name.nil? }
                       .reject { |file| non_upgrade_set.include?(file.name) }
                       .select { |file| file.name.end_with?(".swift") }

  # It is assumed that all Swift files we're including are contained in the root group, or 1 group deep
  swift_filenames_to_group_name = swift_files.each_with_object({}) { |file, object| object[file.name] = file.parent.name }

  manifest_path = File.expand_path(File.join(swift_folder, "/upgrade_manifest.json"))
  File.write(manifest_path, swift_filenames_to_group_name.to_json)

  UI.success("Done generating FastlaneSwiftRunner project manifest")
  manifest_path
end

desc "Does everything that's needed for a release"
desc "This includes running tests and verifying the GitHub release"
lane :release do
  verify_env_variables
  slack_train_start(distance: 2,
                       train: "🚀",
           reverse_direction: true,
                        rail: "✨")

  update_fastlane
  slack_train

  # Git verification
  #
  ensure_git_status_clean
  ensure_git_branch(branch: 'master')
  git_pull

  validate_repo

  # Verifying RubyGems version
  #
  version = local_version
  old_version = current_version
  puts("Deploying #{version}")
  if Gem::Version.new(version) <= Gem::Version.new(old_version)
    UI.user_error!("Version number #{version} was already deployed")
  end

  # Then push to git remote
  #
  push_to_git_remote

  # Preparing GitHub Release
  #
  github_release = get_github_release(url: "fastlane/fastlane", version: version)
  if (github_release || {}).fetch('body', '').length == 0
    show_changelog(old_version: old_version)

    title = prompt(text: 'Title: ')
    description = prompt(text: "Please enter a changelog (make sure to rephrase changes to make it easy to understand, and remove non-important changes that don't affect the end-user): ",
                         multi_line_end_keyword: "END")

    github_release = set_github_release(
      repository_name: "fastlane/fastlane",
      name: [version, title].join(" "),
      tag_name: version,
      description: description,
      is_draft: false
    )

    # Actual release of the gem
    # Using IO.popen because `gem push` will prompt for 2FA if enabled
    #
    command = "gem push ../pkg/fastlane-#{version}.gem"
    IO.popen(command) do |io|
      io.each do |line|
        puts(line)
      end
    end

    release_url = github_release['html_url']

    message = [title, description, release_url].join("\n\n")
    add_fastlane_git_tag(tag: "fastlane/#{version}", message: message)
  end

  # After publishing
  #
  if ENV['SLACK_URL']
    release_notes = github_release['body']
    # markup - turn github references into links
    release_notes.gsub!(/\(#([0-9]+)\)/, '(<https://github.com/fastlane/fastlane/issues/\1|#\1>)')
    slack_message = "Successfully released [fastlane #{version}](#{release_url}) :rocket:"
    slack(
      channel: "releases",
      default_payloads: [],
      message: slack_message,
      payload: {
        "New" => release_notes
      }
    )
    slack(channel: "action", default_payloads: [], message: slack_message)
  end

  clubmate

  puts("You can now tweet:".green)
  releases_url = "https://github.com/fastlane/fastlane/releases/tag/#{version}"
  puts("[fastlane] #{github_release['name']} #{releases_url}")

  send_mac_app_ci_reminder

  update_docs(version: version)
  slack_train
end

desc "Notifies Fabric Slack to run CI Job for Mac App"
private_lane :send_mac_app_ci_reminder do
  if ENV['FABRIC_SLACK_URL']
    slack(
      slack_url: ENV['FABRIC_SLACK_URL'],
      channel: 'deployment-tools',
      default_payloads: [],
      message: "Please run the Fastlane Mac App Package CI job in TeamCity\n#{ENV['FABRIC_MAC_APP_CI_JOB_URL']}"
    )
  end
end

desc "Print out the changelog since the last tagged release and open the GitHub page with the changes"
lane :show_changelog do |options|
  old_version = options[:old_version] || current_version

  changes = sh("git log --pretty='* %s via %aN' #{old_version}...HEAD --no-merges ..", log: $verbose).gsub("\n\n", "\n")
  changes.gsub!("[WIP]", "") # sometimes a [WIP] is merged

  github_diff_url = "https://github.com/fastlane/fastlane/compare/#{old_version}...master"
  sh("open #{github_diff_url}")

  puts("Changes since release #{old_version}:\n\n#{changes.cyan}")
  changes # return the text without the modified colors
end

desc "Add a git tag in the fastlane repo for this release"
private_lane :add_fastlane_git_tag do |options|
  `git tag -am #{options[:message].shellescape} #{options[:tag].shellescape}`
  push_git_tags
end

# Docs

desc "Validates the docs still are good"
lane :validate_docs do
  # Validate docs content
  ensure_tool_name_formatting
  ensure_code_samples
  ensure_special_docs_code_samples
  ensure_code_snippets
  # (Validate action documentation)
  ensure_actions_config_items_formatting

  # Test if generating the docs is successful
  clone_docs do
    generate_markdown_docs(target_path: ".")
  end

  # Verify docs are still working
  verify_docs
end

desc "Makes sure the tests on https://docs.fastlane.tools still work with the latest version"
lane :verify_docs do
  clone_docs do
    Bundler.with_clean_env do
      puts(`sed -i -e "s/activate_bin_path/bin_path/g" $(which bundle)`) # workaround for bundler https://github.com/bundler/bundler/issues/4602#issuecomment-233619696
      sh("bundle install")
      sh("bundle exec fastlane test skip_building:true") # skip_building since we don't have a proper python environment set up
    end
  end
end

desc "Update the actions.md on https://docs.fastlane.tools"
desc "This will also automatically submit a pull request to fastlane/docs"
lane :update_docs do |options|
  debug = options[:debug]
  version = options[:version]

  unless debug
    verify_env_variables
    ensure_actions_config_items_formatting
  end

  template_path = File.expand_path("./assets/render_plugin.md.erb")
  clone_docs(debug: debug) do
    plugin_scores_cache_path = File.expand_path("./plugin_scores_cache.yml")
    docs_path = generate_markdown_docs(target_path: ".")
    yml_path = File.expand_path("./mkdocs.yml")
    actions_md_path = File.expand_path(File.join(docs_path, "docs/actions.md"))
    action_docs = Dir[File.join(docs_path, "docs", "actions", "*")].collect do |current|
      File.expand_path(current) # to make sure we commit the change
    end

    # Copy over the custom assets
    custom_action_docs_path = "lib/fastlane/actions/docs/"
    custom_assets = Dir[File.join(Fastlane::ROOT, custom_action_docs_path, "assets", "*")].collect do |current_asset_path|
      current_output_path = File.join("docs/img/actions", File.basename(current_asset_path))
      FileUtils.cp(current_asset_path, current_output_path)

      File.expand_path(current_output_path) # to make sure we commit the change
    end

    unless options[:skip_bundle_update]
      Bundler.with_clean_env do
        sh("bundle update")
      end
    end

    if `git status --porcelain`.length == 0
      UI.success("No changes in the actions.md ✅")
    else
      # Create a new branch
      sh("git checkout -b 'update-actions-md-#{Time.now.to_i}'") unless debug
      plugins_path = "docs/plugins/available-plugins.md"
      unless options[:skip_plugin_scores]
        plugin_scores(template_path: template_path,
                        output_path: plugins_path,
                         cache_path: plugin_scores_cache_path)
      end

      next if debug

      Dir.chdir("fastlane") do # this is an assumption of fastlane, that we have to .. when shelling out
        # Commit the changes
        changes_to_commit = [plugin_scores_cache_path, actions_md_path, "Gemfile.lock", plugins_path, yml_path] + action_docs + custom_assets
        git_add(path: changes_to_commit)
        git_commit(path: changes_to_commit,
                message: "Update docs for latest fastlane release #{version} (actions.md, available-plugins.md) 🚀")
        # Push them to the git remote
        push_to_git_remote

        # Submit the pull request
        pr_url = create_pull_request(
          api_token: ENV["FL_GITHUB_RELEASE_API_TOKEN"],
          repo: "fastlane/docs",
          title: "[Bot] Update docs for latest fastlane release #{version} (actions.md, available-plugins.md) 🚀",
          body: "Auto-generated by _fastlane_ bot 🤖"
        )
        UI.success("Successfully submitted a pull request to fastlane/docs: #{pr_url} 🚀")
      end
    end
  end
end

def clone_docs(debug: false)
  if debug
    clone_url = ENV['FASTLANE_DOCS_CLONE_URL'] || "../../docs"

    Dir.chdir(clone_url) do
      yield
    end
  else
    require 'tmpdir'
    git_url = ENV['FASTLANE_DOCS_GIT_URL'] || "https://github.com/fastlane/docs"

    Dir.mktmpdir("fl_clone") do |tmp_dir|
      Dir.chdir(tmp_dir) do
        sh("git clone #{git_url} --depth=1")
        Dir.chdir("docs") do
          yield
        end
      end
    end
  end
end

def generate_markdown_docs(target_path: nil)
  require 'fastlane/documentation/markdown_docs_generator'
  Fastlane::MarkdownDocsGenerator.new.generate!(target_path: File.expand_path(target_path))
  return target_path
end

# Exception Handling

error do |lane, exception|
  if ENV['SLACK_URL']
    slack(channel: "testing", message: exception.to_s, success: false)
  end
  slack_train_crash
end

# Helper

desc "Ensure all the requirement environment variables are provided"
desc "this way the deployment script will fail early (and often)"
private_lane :verify_env_variables do
  ensure_env_vars(env_vars: ['GITHUB_USER_NAME', 'GITHUB_API_TOKEN'])

  UI.user_error!("You're not logged in RubyGems. Log in using `gem push` if using RubyGems < 2.7.0 or `gem signin` if using RubyGems >=2.7.0") unless File.file?(File.expand_path("~/.gem/credentials"))
end

desc "Get the local version number per version.rb"
private_lane :local_version do
  require_relative "../fastlane/lib/fastlane/version.rb"

  Fastlane::VERSION
end

desc "Get the version number of the last release"
private_lane :current_version do
  puts("Checking the latest version on RubyGems")
  download(url: "https://rubygems.org/api/v1/gems/fastlane.json")["version"]
end

desc "Ensure the correct formatting for the fastlane tools"
private_lane :ensure_tool_name_formatting do
  UI.message("🕗  Verifying tool name formatting...")
  require 'fastlane/tools'
  errors = []
  Dir.chdir("..") do
    Dir["**/*.md"].each do |path|
      content = File.read(path)
      Fastlane::TOOLS.each do |tool|
        errors << "Use _#{tool}_ instead of `#{tool}` to mention a tool in the docs in '#{path}'" if content.include?("`#{tool}`")
        errors << "Use _#{tool}_ instead of `_#{tool}_` to mention a tool in the docs in '#{path}'" if content.include?("`_#{tool}_`")
        errors << "Use [_#{tool}_] instead of [#{tool}] to mention a tool in the docs in '#{path}'" if content.include?("[#{tool}]")
        errors << "Use <em>#{tool}<em> instead of <code>#{tool}</code> to mention a tool in the docs in '#{path}'" if content.include?("<code>#{tool}</code>")
        if content.include?("_#{tool.to_s.capitalize}_") || content.include?("`#{tool.to_s.capitalize}`")
          errors << "fastlane tools have to be formatted in lower case: #{tool} in '#{path}'"
        end
      end
    end
  end
  errors.each { |a| UI.error(a) }
  UI.user_error!("Invalid formatting of one of the fastlane tools") unless errors.empty?
  UI.success("✅  fastlane tools formatting is correct")
end

# Run the code samples, yo
private_lane :ensure_code_samples do
  UI.message("🕗  Verifying all action code samples work with the current fastlane release")
  all_content = ""
  count_actions = 0
  ActionsList.all_actions do |action|
    all_content += "```ruby\n"
    all_content += action.example_code.map { |code| code.gsub(/^\s+/, '') }.join("\n") if action.example_code
    all_content += "\n```"
    count_actions += 1
  end
  test_sample_code(content: all_content) # to not have to call the action 200 times
  UI.success("✅  All fastlane action code samples (from #{count_actions} actions) work as expected")
end

# Run the other code samples, yo
private_lane :ensure_special_docs_code_samples do
  UI.message("🕗  Verifying all action special docs (`fastlane/lib/fastlane/actions/docs`) code samples work with the latest fastlane release")
  all_content = ""
  files = Dir["../fastlane/lib/fastlane/actions/docs/*.md"]
  files.each do |special_docs_page_path|
    all_content += File.read(special_docs_page_path)
  end
  test_sample_code(content: all_content) # to not have to call the action 200 times
  UI.success("✅  All fastlane action special docs code samples (from #{files.length} files) work as expected")
end

private_lane :ensure_code_snippets do
  UI.message("🕗  Verifying all code snippets are correctly formatted")

  shell_commands_start = '((bundle|fastlane)[ ]|[A-Z_]+=)'
  errors = []

  require 'fastlane/documentation/markdown_docs_generator'

  Fastlane::MarkdownDocsGenerator.new.actions_md_contents.each do |action_name, content|
    errors << "Use '```no-highlight ↵ <code snippet> ↵ ```' instead of '```<language> ↵ <code snippet> ↵ ```' for code snippets for action '#{action_name}'" if content =~ /```(?<!no-higlight)\w+\s*#{shell_commands_start}/
    errors << "Use '```no-highlight ↵ <code snippet> ↵ ```' instead of '    <code snippet>' for code snippets for action '#{action_name}'" if content =~ /^[ ]{4}#{shell_commands_start}/
  end

  errors.each { |a| UI.error(a) }

  UI.user_error!("Invalid formatting of one of the code snippets") unless errors.empty?
  UI.success("✅  All code snippets are formatted as expected")
end

private_lane :ensure_actions_config_items_formatting do
  UI.message("🕗  Verifying actions' config items formatting...")

  errors = []

  require 'fastlane_core/configuration/config_item'

  ActionsList.all_actions do |action|
    next if action.available_options.nil?

    action.available_options.each do |option|
      next unless option.kind_of?(FastlaneCore::ConfigItem)

      errors << "Remove the '\\n' from the config item ':#{option.key}' of the action '#{action.action_name}'" if option.description && option.description =~ /\n|\\n/
    end
  end

  errors.each { |a| UI.error(a) }

  UI.user_error!("Invalid formatting of one of the actions' config items") unless errors.empty?
  UI.success("✅  fastlane actions' config items formatting is correct")
end

```
</details>

**No Appfile found**


### fastlane gems

| Gem      | Version | Update-Status      |
| -------- | ------- | ------------------ |
| fastlane | 2.171.0 | 🚫 Update available |


### Loaded fastlane plugins:

| Plugin                      | Version | Update-Status |
| --------------------------- | ------- | ------------- |
| fastlane-plugin-ruby        | 0.1.3   | ✅ Up-To-Date  |
| fastlane-plugin-clubmate    | 0.1.0   | ✅ Up-To-Date  |
| fastlane-plugin-slack_train | 0.2.0   | ✅ Up-To-Date  |


<details><summary><b>Loaded gems</b></summary>

| Gem                           | Version      |
| ----------------------------- | ------------ |
| did_you_mean                  | 1.2.0        |
| slack-notifier                | 2.3.2        |
| rouge                         | 2.0.7        |
| xcpretty                      | 0.3.0        |
| terminal-notifier             | 2.0.0        |
| terminal-table                | 1.8.0        |
| addressable                   | 2.7.0        |
| multipart-post                | 2.0.0        |
| word_wrap                     | 1.0.0        |
| colored                       | 1.2          |
| highline                      | 1.7.10       |
| commander-fastlane            | 4.4.6        |
| faraday_middleware            | 1.0.0        |
| gh_inspector                  | 1.1.3        |
| rubyzip                       | 2.3.0        |
| security                      | 0.1.3        |
| uber                          | 0.1.0        |
| declarative-option            | 0.1.0        |
| representable                 | 3.0.4        |
| retriable                     | 3.1.2        |
| mini_mime                     | 1.0.2        |
| httpclient                    | 2.8.3        |
| google-api-client             | 0.38.0       |
| nanaimo                       | 0.3.0        |
| colored2                      | 3.1.2        |
| claide                        | 1.0.3        |
| CFPropertyList                | 3.0.3        |
| atomos                        | 0.1.3        |
| xcodeproj                     | 1.19.0       |
| unicode-display_width         | 1.7.0        |
| plist                         | 3.6.0        |
| public_suffix                 | 4.0.6        |
| tty-screen                    | 0.8.1        |
| tty-cursor                    | 0.7.1        |
| tty-spinner                   | 0.9.3        |
| babosa                        | 1.0.4        |
| excon                         | 0.78.1       |
| unf_ext                       | 0.0.7.7      |
| unf                           | 0.1.4        |
| domain_name                   | 0.5.20190701 |
| http-cookie                   | 1.0.3        |
| ruby2_keywords                | 0.0.4        |
| faraday-net_http              | 1.0.1        |
| faraday                       | 1.3.0        |
| faraday-cookie_jar            | 0.0.7        |
| fastimage                     | 2.2.1        |
| json                          | 2.5.1        |
| mini_magick                   | 4.11.0       |
| xcpretty-travis-formatter     | 1.0.1        |
| dotenv                        | 2.7.6        |
| bundler                       | 2.2.4        |
| naturally                     | 2.2.1        |
| simctl                        | 1.6.8        |
| jwt                           | 2.2.2        |
| declarative                   | 0.0.20       |
| multi_json                    | 1.15.0       |
| signet                        | 0.14.0       |
| os                            | 1.1.1        |
| memoist                       | 0.16.2       |
| googleauth                    | 0.14.0       |
| rake                          | 13.0.3       |
| digest-crc                    | 0.6.3        |
| rexml                         | 3.2.4        |
| google-apis-core              | 0.2.0        |
| google-apis-storage_v1        | 0.1.0        |
| google-apis-iamcredentials_v1 | 0.1.0        |
| google-cloud-errors           | 1.0.1        |
| google-cloud-env              | 1.4.0        |
| google-cloud-core             | 1.5.0        |
| google-cloud-storage          | 1.30.0       |
| emoji_regex                   | 3.2.1        |
| aws-eventstream               | 1.1.0        |
| aws-sigv4                     | 1.2.2        |
| aws-partitions                | 1.417.0      |
| jmespath                      | 1.4.0        |
| aws-sdk-core                  | 3.111.2      |
| aws-sdk-kms                   | 1.41.0       |
| aws-sdk-s3                    | 1.87.0       |
| date                          | 1.0.0        |
| stringio                      | 0.0.1        |
| zlib                          | 1.0.0        |
| openssl                       | 2.1.2        |
| strscan                       | 1.0.0        |
| fileutils                     | 1.0.2        |
| etc                           | 1.0.0        |
| io-console                    | 0.4.6        |
| ipaddr                        | 1.2.0        |
| mini_portile2                 | 2.1.0        |
| pkg-config                    | 1.1.9        |
| nokogiri                      | 1.6.8        |
| psych                         | 3.0.2        |
| ox                            | 2.14.0       |
| fastlane-plugin-ruby          | 0.1.3        |
| fastlane-plugin-clubmate      | 0.1.0        |
| fastlane-plugin-slack_train   | 0.2.0        |
</details>


*generated on:* **2021-01-23**
</details>



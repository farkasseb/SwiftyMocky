use_frameworks!

def tests
    pod 'SwiftyMocky', :path => './'
end

target 'Mocky_Example_iOS' do
    platform :ios, '12.0'
    target 'Mocky_Tests_iOS' do
        inherit! :search_paths
        tests
    end
end

target 'Mocky_Example_iOS_15' do
    platform :ios, '12.0'
    target 'Mocky_Tests_iOS_15' do
        inherit! :search_paths
        tests
    end
end

target 'Mocky_Example_tvOS' do
    platform :tvos, '12'
    target 'Mocky_Tests_tvOS' do
        inherit! :search_paths
        tests
    end
end

target 'Mocky_Example_macOS' do
    platform :macos, '10.15'
    target 'Mocky_Tests_macOS' do
        inherit! :search_paths
        tests
    end
end
